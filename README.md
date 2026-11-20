<p align="center">
  <img src="https://img.shields.io/badge/🏦_Awesome-LLM_&_Finance-gold?style=for-the-badge&logoColor=white" alt="Awesome LLM & Finance"/>
</p>

<h1 align="center">Awesome LLM & Finance</h1>

<p align="center">
  <strong>A curated collection of the most impactful Large Language Model resources for the financial industry</strong>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/Resources-200%2B-blue?style=flat-square" alt="Resources"/>
  <img src="https://img.shields.io/badge/Categories-15%2B-green?style=flat-square" alt="Categories"/>
  <img src="https://img.shields.io/badge/Papers-30%2B-red?style=flat-square" alt="Papers"/>
  <img src="https://img.shields.io/badge/Datasets-25%2B-orange?style=flat-square" alt="Datasets"/>
  <img src="https://img.shields.io/badge/Models-20%2B-purple?style=flat-square" alt="Models"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/github/last-commit/simon-pierreboucher/awesome-llm-finance?style=flat-square&color=teal" alt="Last Commit"/>
  <img src="https://img.shields.io/github/stars/simon-pierreboucher/awesome-llm-finance?style=flat-square&color=gold" alt="Stars"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Market_Size-$5.73B_(2024)-informational?style=flat-square&logo=bitcoin&logoColor=white" alt="Market Size"/>
  <img src="https://img.shields.io/badge/Projected-$130.65B_(2034)-success?style=flat-square&logo=trending-up&logoColor=white" alt="Projected"/>
  <img src="https://img.shields.io/badge/CAGR-36.8%25-critical?style=flat-square" alt="CAGR"/>
  <img src="https://img.shields.io/badge/RegTech_Market-$14.94B_(2024)-blueviolet?style=flat-square" alt="RegTech"/>
</p>

---

## Table of Contents

- [About](#about)
- [Finance-Specific LLMs](#-finance-specific-llms)
- [Sentiment Analysis](#-sentiment-analysis)
- [Trading Agents & Frameworks](#-trading-agents--frameworks)
- [RAG for Finance](#-rag-for-finance)
- [LLM-Powered Financial Agents](#-llm-powered-financial-agents)
- [Quantitative Finance & Alpha Generation](#-quantitative-finance--alpha-generation)
- [Risk Management](#-risk-management)
- [Fraud Detection](#-fraud-detection)
- [Financial Report Generation](#-financial-report-generation)
- [ESG & Sustainability](#-esg--sustainability)
- [Regulatory & Compliance (RegTech)](#-regulatory--compliance-regtech)
- [Crypto, DeFi & Web3](#-crypto-defi--web3)
- [Datasets](#-datasets)
- [Benchmarks & Evaluation](#-benchmarks--evaluation)
- [Research Papers](#-research-papers)
- [Fine-Tuning & Adaptation](#-fine-tuning--adaptation)
- [APIs & Data Platforms](#-apis--data-platforms)
- [Courses & Tutorials](#-courses--tutorials)
- [Companies & Startups](#-companies--startups)
- [Prompt Engineering for Finance](#-prompt-engineering-for-finance)
- [Related Awesome Lists](#-related-awesome-lists)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

---

## About

> The intersection of **Large Language Models** and **Finance** is reshaping how we analyze markets, manage risk, detect fraud, and make investment decisions. This awesome list aims to be the most comprehensive, well-organized, and up-to-date resource for researchers, practitioners, and enthusiasts working at this frontier.

<p align="center">
  <img src="https://img.shields.io/badge/Last_Updated-February_2026-blue?style=for-the-badge" alt="Last Updated"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge" alt="PRs Welcome"/>
</p>

---

## 🧠 Finance-Specific LLMs

> Large Language Models specifically designed, pre-trained, or fine-tuned for financial tasks.

| Model | Repository | Description | Badges |
|-------|-----------|-------------|--------|
| **FinGPT** | [AI4Finance-Foundation/FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | Open-source financial LLM with data-centric approach. LoRA fine-tuning costs under $300. Outperforms GPT-4 on financial sentiment tasks. | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square&color=gold) ![Last Commit](https://img.shields.io/github/last-commit/AI4Finance-Foundation/FinGPT?style=flat-square) |
| **BloombergGPT** | [Paper](https://arxiv.org/abs/2303.17564) | 50B parameter LLM trained on 363B tokens of Bloomberg financial data. The gold standard for domain-specific financial LLMs. | ![Paper](https://img.shields.io/badge/arXiv-2303.17564-b31b1b?style=flat-square&logo=arxiv) ![Params](https://img.shields.io/badge/Params-50B-blue?style=flat-square) |
| **PIXIU / FinMA** | [The-FinAI/PIXIU](https://github.com/The-FinAI/PIXIU) | Open-source framework with FinMA models (7B & 30B), FIT instruction dataset (136K samples), and FinBen evaluation benchmark. NeurIPS 2023. | ![Stars](https://img.shields.io/github/stars/The-FinAI/PIXIU?style=flat-square&color=gold) ![Paper](https://img.shields.io/badge/NeurIPS-2023-purple?style=flat-square) |
| **FinTral** | [UBC-NLP/fintral](https://github.com/UBC-NLP/fintral) | GPT-4 level multimodal financial LLM built on Mistral-7B. Integrates text, numerical, tabular, and image data. Outperforms GPT-4 on 5/9 tasks. | ![Stars](https://img.shields.io/github/stars/UBC-NLP/fintral?style=flat-square&color=gold) ![Paper](https://img.shields.io/badge/arXiv-2402.10986-b31b1b?style=flat-square&logo=arxiv) |
| **DISC-FinLLM** | [FudanDISC/DISC-FinLLM](https://github.com/FudanDISC/DISC-FinLLM) | Chinese financial LLM with 4 specialized modules: consulting, text analysis, calculation, and knowledge retrieval. | ![Stars](https://img.shields.io/github/stars/FudanDISC/DISC-FinLLM?style=flat-square&color=gold) ![Language](https://img.shields.io/badge/Language-Chinese-red?style=flat-square) |
| **CFGPT** | [TongjiFinLab/CFGPT](https://github.com/TongjiFinLab/CFGPT) | Chinese Financial Assistant LLM pre-trained on financial announcements, articles, exams, news, and research papers. | ![Stars](https://img.shields.io/github/stars/TongjiFinLab/CFGPT?style=flat-square&color=gold) ![Language](https://img.shields.io/badge/Language-Chinese-red?style=flat-square) |
| **InvestLM** | [AbaciNLP/InvestLM](https://github.com/AbaciNLP/InvestLM) | LLaMA-65B fine-tuned on CFA exam questions, SEC filings, and StackExchange quant discussions. Rated comparable to GPT-4 by hedge fund managers. | ![Stars](https://img.shields.io/github/stars/AbaciNLP/InvestLM?style=flat-square&color=gold) ![Paper](https://img.shields.io/badge/arXiv-2309.13064-b31b1b?style=flat-square&logo=arxiv) |
| **XuanYuan 2.0** | [Paper](https://dl.acm.org/doi/10.1145/3583780.3615285) | BLOOM-176B based model with hybrid-tuning for Chinese financial domain. Hundreds of billions of parameters. | ![Paper](https://img.shields.io/badge/CIKM-2023-orange?style=flat-square) ![Params](https://img.shields.io/badge/Params-176B-blue?style=flat-square) |
| **NumLLM** | [Paper](https://arxiv.org/abs/2405.00566) | Numeric-sensitive LLM addressing numeric reasoning challenges in Chinese financial texts. | ![Paper](https://img.shields.io/badge/arXiv-2405.00566-b31b1b?style=flat-square&logo=arxiv) |

---

## 📊 Sentiment Analysis

> Models and tools for analyzing financial sentiment from news, social media, and reports.

| Tool | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **FinBERT (ProsusAI)** | [ProsusAI/finBERT](https://github.com/ProsusAI/finBERT) | The most widely-used pre-trained model for financial sentiment analysis. 97% accuracy on Financial PhraseBank. | ![Stars](https://img.shields.io/github/stars/ProsusAI/finBERT?style=flat-square&color=gold) ![HuggingFace](https://img.shields.io/badge/🤗-Model-yellow?style=flat-square) |
| **FinBERT (yya518)** | [yya518/FinBERT](https://github.com/yya518/FinBERT) | BERT pre-trained on financial communications. Fine-tuned on 10K analyst report sentences. SOTA on multiple financial NLP tasks. | ![Stars](https://img.shields.io/github/stars/yya518/FinBERT?style=flat-square&color=gold) |
| **Financial Sentiment with ChatGPT** | [giorgosfatouros/Financial-Sentiment-Analysis-with-ChatGPT](https://github.com/giorgosfatouros/Financial-Sentiment-Analysis-with-ChatGPT) | Research code exploring ChatGPT 3.5 for financial sentiment analysis in the forex market. | ![Stars](https://img.shields.io/github/stars/giorgosfatouros/Financial-Sentiment-Analysis-with-ChatGPT?style=flat-square&color=gold) |
| **LLM Fine-Tuning for Sentiment** | [KaifAhmad1/LLM-FineTuning-for-Sentiment-Classification](https://github.com/KaifAhmad1/LLM-FineTuning-for-Sentiment-Classification) | Fine-tuning Microsoft Phi-2 for financial news sentiment. Improved accuracy from 0.349 to 0.872. | ![Stars](https://img.shields.io/github/stars/KaifAhmad1/LLM-FineTuning-for-Sentiment-Classification?style=flat-square&color=gold) ![Accuracy](https://img.shields.io/badge/Accuracy-87.2%25-brightgreen?style=flat-square) |

---

## 🤖 Trading Agents & Frameworks

> LLM-powered trading systems, autonomous agents, and reinforcement learning frameworks for financial markets.

| Tool | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **TradingAgents** | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | Multi-agent LLM framework mirroring real-world trading firms. Specialized agents for fundamental, sentiment, technical analysis, trading, and risk management. | ![Stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat-square&color=gold) ![Last Commit](https://img.shields.io/github/last-commit/TauricResearch/TradingAgents?style=flat-square) |
| **FinRL** | [AI4Finance-Foundation/FinRL](https://github.com/AI4Finance-Foundation/FinRL) | First open-source DRL framework for quantitative finance. Supports DQN, DDPG, PPO, SAC, A2C, TD3. NeurIPS 2020 & ICAIF 2021. | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL?style=flat-square&color=gold) ![Paper](https://img.shields.io/badge/NeurIPS-2020-purple?style=flat-square) |
| **FinRobot** | [AI4Finance-Foundation/FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | Open-source AI agent platform unifying LLMs, RL, and quantitative analytics. Financial Chain-of-Thought prompting. | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square&color=gold) ![Last Commit](https://img.shields.io/github/last-commit/AI4Finance-Foundation/FinRobot?style=flat-square) |
| **FinRL-Meta** | [AI4Finance-Foundation/FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | Dynamic datasets and market environments for FinRL. DataOps paradigm for continuous DRL benchmark production. | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square&color=gold) |
| **FinMem** | [pipiku915/FinMem-LLM-StockTrading](https://github.com/pipiku915/FinMem-LLM-StockTrading) | LLM trading agent with layered memory (working, episodic, semantic) and character design. ICLR Workshop. | ![Stars](https://img.shields.io/github/stars/pipiku915/FinMem-LLM-StockTrading?style=flat-square&color=gold) ![Paper](https://img.shields.io/badge/ICLR-Workshop-blue?style=flat-square) |
| **StockAgent** | [MingyuJ666/Stockagent](https://github.com/MingyuJ666/Stockagent) | Multi-agent AI system simulating investor trading behaviors in real stock market conditions. | ![Stars](https://img.shields.io/github/stars/MingyuJ666/Stockagent?style=flat-square&color=gold) |
| **AgentQuant** | [OnePunchMonk/AgentQuant](https://github.com/OnePunchMonk/AgentQuant) | Autonomous quantitative trading research platform. Transforms stock lists into fully backtested strategies using AI agents — no coding required. | ![Stars](https://img.shields.io/github/stars/OnePunchMonk/AgentQuant?style=flat-square&color=gold) |
| **LLM-TradeBot** | [EthanAlgoX/LLM-TradeBot](https://github.com/EthanAlgoX/LLM-TradeBot) | Multi-agent AI trading system using LLMs to optimize strategies and adapt to market conditions in real-time. | ![Stars](https://img.shields.io/github/stars/EthanAlgoX/LLM-TradeBot?style=flat-square&color=gold) |

---

## 📚 RAG for Finance

> Retrieval-Augmented Generation systems specialized for financial document analysis, SEC filings, and financial knowledge bases.

| Tool | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **FinanceRAG** | [cv-lee/FinanceRAG](https://github.com/cv-lee/FinanceRAG) | Competition-grade financial RAG system built for ACM-ICAIF '24. Multi-stage reranking and long-context management. | ![Stars](https://img.shields.io/github/stars/cv-lee/FinanceRAG?style=flat-square&color=gold) ![Conference](https://img.shields.io/badge/ICAIF-2024-blue?style=flat-square) |
| **FinanceRAG Investment Assistant** | [nik2401/FinanceRAG-Investment-Research-Assistant](https://github.com/nik2401/FinanceRAG-Investment-Research-Assistant) | AI-powered SEC filing analysis using RAG. Reduces 4-hour document analysis to 3 seconds with 90%+ accuracy. | ![Stars](https://img.shields.io/github/stars/nik2401/FinanceRAG-Investment-Research-Assistant?style=flat-square&color=gold) ![Speed](https://img.shields.io/badge/Speed-4800x_Faster-brightgreen?style=flat-square) |
| **KG-RAG (Vector Institute)** | [VectorInstitute/kg-rag](https://github.com/VectorInstitute/kg-rag) | Knowledge Graph + RAG framework for SEC 10-Q filings. Explores how knowledge graphs improve financial information retrieval. | ![Stars](https://img.shields.io/github/stars/VectorInstitute/kg-rag?style=flat-square&color=gold) |
| **Financial Agentic RAG** | [DeepakSilaych/Financial_Agentic_RAG](https://github.com/DeepakSilaych/Financial_Agentic_RAG) | Agentic RAG using LangGraph for analyzing 10-K filings, combining structured retrieval with agentic reasoning. | ![Stars](https://img.shields.io/github/stars/DeepakSilaych/Financial_Agentic_RAG?style=flat-square&color=gold) |
| **SEC-RAG** | [sheikhhanif/SEC-RAG](https://github.com/sheikhhanif/SEC-RAG) | Extracts specific sections from 10-Q filings and analyzes them using a RAG approach. | ![Stars](https://img.shields.io/github/stars/sheikhhanif/SEC-RAG?style=flat-square&color=gold) |
| **FinsightRAG** | [insculptor/FinsightRAG](https://github.com/insculptor/FinsightRAG) | Production-level RAG pipeline for financial terms using Investopedia's database. Summarizes, retrieves, reranks, and generates. | ![Stars](https://img.shields.io/github/stars/insculptor/FinsightRAG?style=flat-square&color=gold) |
| **FinSage** | [HFHL/finsage](https://github.com/HFHL/finsage) | Intelligent RAG framework for compliance analysis in financial document workflows. | ![Stars](https://img.shields.io/github/stars/HFHL/finsage?style=flat-square&color=gold) |
| **RAG Multimodal Finance** | [Mattral/RAG-Multimodal-Financial-Document-Analysis-and-Recall](https://github.com/Mattral/RAG-Multimodal-Financial-Document-Analysis-and-Recall) | Multimodal RAG using GPT-4V vision to identify and describe graphs from financial documents. | ![Stars](https://img.shields.io/github/stars/Mattral/RAG-Multimodal-Financial-Document-Analysis-and-Recall?style=flat-square&color=gold) |
| **RAGFlow** | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | Leading open-source RAG engine fusing RAG with Agent capabilities. General-purpose with strong finance applications. | ![Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square&color=gold) ![Last Commit](https://img.shields.io/github/last-commit/infiniflow/ragflow?style=flat-square) |

---

## 🏢 LLM-Powered Financial Agents

> Autonomous agents for investment research, financial analysis, and portfolio management.

| Agent | Repository | Description | Badges |
|-------|-----------|-------------|--------|
| **Dexter** | [virattt/dexter](https://github.com/virattt/dexter) | Autonomous agent for deep financial research with task planning, self-reflection, and real-time market data. | ![Stars](https://img.shields.io/github/stars/virattt/dexter?style=flat-square&color=gold) |
| **Deep Research Agent for Finance** | [The-AI-Alliance/deep-research-agent-for-finance](https://github.com/The-AI-Alliance/deep-research-agent-for-finance) | AI Alliance project for automated financial research, gathering data from multiple sources into structured investment reports. | ![Stars](https://img.shields.io/github/stars/The-AI-Alliance/deep-research-agent-for-finance?style=flat-square&color=gold) |
| **AI Financial Agent** | [virattt/ai-financial-agent](https://github.com/virattt/ai-financial-agent) | Lightweight autonomous agent for investment research. | ![Stars](https://img.shields.io/github/stars/virattt/ai-financial-agent?style=flat-square&color=gold) |
| **Yahoo Finance LLM Agent** | [ojasskapre/yahoo-finance-llm-agent](https://github.com/ojasskapre/yahoo-finance-llm-agent) | Combines OpenAI LLMs with Yahoo Finance API and LangChain for real-time financial data via interactive chat. | ![Stars](https://img.shields.io/github/stars/ojasskapre/yahoo-finance-llm-agent?style=flat-square&color=gold) |
| **Personal Finance Agent** | [Kirushikesh/Personal-Finance-Agent](https://github.com/Kirushikesh/Personal-Finance-Agent) | LLM agent monitoring personal finance for data analysis, summarization, and financial operations. | ![Stars](https://img.shields.io/github/stars/Kirushikesh/Personal-Finance-Agent?style=flat-square&color=gold) |
| **LLM Finance Agent** | [GURPREETKAURJETHRA/LLM-based-Finance-Agent](https://github.com/GURPREETKAURJETHRA/LLM-based-Finance-Agent) | Intelligent agent using LLMs for automated financial news retrieval and stock price prediction. | ![Stars](https://img.shields.io/github/stars/GURPREETKAURJETHRA/LLM-based-Finance-Agent?style=flat-square&color=gold) |

---

## 📈 Quantitative Finance & Alpha Generation

> LLM-based tools for quantitative trading, alpha factor mining, and strategy discovery.

| Tool | Repository / Link | Description | Badges |
|------|-------------------|-------------|--------|
| **QuantConnect + MCP** | [quantconnect.com/mcp](https://www.quantconnect.com/mcp) | World's leading open algorithmic trading platform. 300K+ users, $45B+ monthly volume. Now with MCP server for LLM integration. | ![Users](https://img.shields.io/badge/Users-300K%2B-blue?style=flat-square) ![Volume](https://img.shields.io/badge/Volume-$45B%2B%2Fmo-green?style=flat-square) |
| **WorldQuant BRAIN** | [platform.worldquantbrain.com](https://platform.worldquantbrain.com/) | Crowdsourced quantitative research platform for building alpha signals. WorldQuant manages ~$9B AUM. | ![AUM](https://img.shields.io/badge/AUM-~$9B-blue?style=flat-square) |
| **Chain-of-Alpha** | [Paper](https://arxiv.org/html/2508.06312v2) | Research framework unleashing LLM power for alpha mining in quantitative trading. | ![Paper](https://img.shields.io/badge/arXiv-Research-b31b1b?style=flat-square&logo=arxiv) |
| **QuantEvolve** | [Paper](https://arxiv.org/html/2510.18569v1) | Multi-agent evolutionary framework for automating quantitative strategy discovery using LLMs. | ![Paper](https://img.shields.io/badge/arXiv-Research-b31b1b?style=flat-square&logo=arxiv) |
| **Automate Strategy Finding** | [Paper](https://arxiv.org/html/2409.06289v4) | LLMs for automated strategy finding. One framework achieved 53.17% cumulative return on SSE50 (Jan 2023 - Jan 2024). | ![Returns](https://img.shields.io/badge/Returns-53.17%25-brightgreen?style=flat-square) |
| **ElliottAgents** | [Paper](https://arxiv.org/html/2506.16813v1) | Multi-agent system integrating Elliott Wave Principle with AI using RAG and deep RL for forecasting. | ![Paper](https://img.shields.io/badge/arXiv-Research-b31b1b?style=flat-square&logo=arxiv) |

---

## 🛡️ Risk Management

> LLM-based tools for credit risk, market risk, and financial risk assessment.

| Tool | Repository / Link | Description | Badges |
|------|-------------------|-------------|--------|
| **CALM** | [colfeng/CALM](https://github.com/colfeng/CALM) | Credit Assessment LLM based on Llama2-chat. Benchmark amalgamates 9 datasets across credit scoring, fraud detection, financial distress, and claim analysis. | ![Stars](https://img.shields.io/github/stars/colfeng/CALM?style=flat-square&color=gold) ![Tasks](https://img.shields.io/badge/Tasks-4-blue?style=flat-square) |
| **Open FinLLM Leaderboard** | [finos-labs/Open-Financial-LLMs-Leaderboard](https://github.com/finos-labs/Open-Financial-LLMs-Leaderboard) | Standardized LLM evaluation across 7 categories including risk management and forecasting. | ![Stars](https://img.shields.io/github/stars/finos-labs/Open-Financial-LLMs-Leaderboard?style=flat-square&color=gold) |
| **Interpretable LLMs for Credit Risk** | [Paper](https://arxiv.org/html/2506.04290v2) | Systematic review analyzing 60 peer-reviewed studies (2020-2025) on LLM-based credit risk assessment using PRISMA methodology. | ![Paper](https://img.shields.io/badge/Studies-60-blue?style=flat-square) ![Period](https://img.shields.io/badge/Period-2020--2025-orange?style=flat-square) |

---

## 🔍 Fraud Detection

> LLM and NLP-based systems for financial fraud detection and prevention.

| Tool | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **Financial Fraud Detection Using LLMs** | [amitkedia007/Financial-Fraud-Detection-Using-LLMs](https://github.com/amitkedia007/Financial-Fraud-Detection-Using-LLMs) | Compares FinBERT and GPT-2 effectiveness in detecting fraudulent activities in financial reports vs traditional ML. | ![Stars](https://img.shields.io/github/stars/amitkedia007/Financial-Fraud-Detection-Using-LLMs?style=flat-square&color=gold) |
| **FraudDetection-LLM-Integration** | [kasturidd/FraudDetection-LLM-Integration](https://github.com/kasturidd/FraudDetection-LLM-Integration) | Isolation Forest + LLM explanations for flagged cases. Enhances transparency and user trust in fraud detection. | ![Stars](https://img.shields.io/github/stars/kasturidd/FraudDetection-LLM-Integration?style=flat-square&color=gold) |
| **Fraud-Detection-LLM** | [nolita26/Fraud-Detection-LLM](https://github.com/nolita26/Fraud-Detection-LLM) | BERT-based fraud detection analyzing transaction data and user behavior patterns. | ![Stars](https://img.shields.io/github/stars/nolita26/Fraud-Detection-LLM?style=flat-square&color=gold) |
| **Real-Time Fraud Detection with RAG** | [Paper](https://arxiv.org/html/2501.15290v1) | Combines RAG with LLMs for real-time fraud detection with enhanced accuracy. | ![Paper](https://img.shields.io/badge/arXiv-2501.15290-b31b1b?style=flat-square&logo=arxiv) |

---

## 📝 Financial Report Generation

> Tools for automated financial report creation, document analysis, and insights generation.

| Tool | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **LLM Financial Report Generator** | [voidbydefault/LLM_Financial_Report_Generator](https://github.com/voidbydefault/LLM_Financial_Report_Generator) | Auto-generates management reports from Excel financial data. Outputs Excel, visualizations, Markdown, and Word. | ![Stars](https://img.shields.io/github/stars/voidbydefault/LLM_Financial_Report_Generator?style=flat-square&color=gold) |
| **Financial Analysis with LLM** | [babdulhakim2/financial-analysis-with-llm](https://github.com/babdulhakim2/financial-analysis-with-llm) | NLP + financial analysis for document analysis with transaction summaries, suspicious trend detection, and entity recognition. | ![Stars](https://img.shields.io/github/stars/babdulhakim2/financial-analysis-with-llm?style=flat-square&color=gold) |
| **Local LLMs Analyse Finance** | [thu-vu92/local-llms-analyse-finance](https://github.com/thu-vu92/local-llms-analyse-finance) | Uses local Llama2 model to automatically categorize bank transaction data. Privacy-preserving. | ![Stars](https://img.shields.io/github/stars/thu-vu92/local-llms-analyse-finance?style=flat-square&color=gold) ![Privacy](https://img.shields.io/badge/Privacy-Local_LLM-green?style=flat-square) |
| **SusGen-GPT** | [Paper](https://arxiv.org/html/2412.10906v1) | Data-centric LLM for financial NLP and sustainability report generation. | ![Paper](https://img.shields.io/badge/arXiv-Research-b31b1b?style=flat-square&logo=arxiv) |

---

## 🌱 ESG & Sustainability

> LLM-powered tools for Environmental, Social, and Governance analysis.

| Tool | Repository / Link | Description | Badges |
|------|-------------------|-------------|--------|
| **Clarity AI** | [clarity.ai](https://clarity.ai/) | Leading ESG intelligence platform. Parses 1.4M+ news pieces daily from 30K+ sources. Covers 98K issuers, 2.3M private companies. BlackRock investor. | ![Coverage](https://img.shields.io/badge/Issuers-98K-blue?style=flat-square) ![Daily](https://img.shields.io/badge/Daily_News-1.4M%2B-green?style=flat-square) |
| **SESAMm** | [sesamm.com](https://www.sesamm.com/) | NLP platform analyzing billions of articles for ESG controversies across 5M+ companies. Raised EUR 35M in 2023. | ![Companies](https://img.shields.io/badge/Companies-5M%2B-blue?style=flat-square) ![Funding](https://img.shields.io/badge/Funding-€35M-green?style=flat-square) |
| **ESG Analysis with RAG** | [mominalix/ESG-Analysis-Using-RAG-Engine](https://github.com/mominalix/ESG-Analysis-Using-Retrieval-Augmented-Generation-Engine) | AI-powered ESG policy gap analysis using LLMs, RAG, and regulatory knowledge base. Built for CSRD/EU Taxonomy compliance. | ![Stars](https://img.shields.io/github/stars/mominalix/ESG-Analysis-Using-Retrieval-Augmented-Generation-Engine?style=flat-square&color=gold) |
| **InferESG** | [ScottLogic/InferESG](https://github.com/ScottLogic/InferESG) | Open-source AI-augmented ESG analysis tool to combat greenwashing and validate ESG claims. | ![Stars](https://img.shields.io/github/stars/ScottLogic/InferESG?style=flat-square&color=gold) |
| **Truvalue Labs** | [truvaluelabs.com](https://brand.truvaluelabs.com/) | FactSet-acquired NLP-based ESG ratings: Insight Score, Pulse Score, Momentum Score, Volume Score. | ![Acquired](https://img.shields.io/badge/Acquired_by-FactSet-blue?style=flat-square) |
| **RepRisk** | [reprisk.com](https://www.reprisk.com/) | AI-driven identification and analysis of ESG risks for financial services and corporate sectors. | ![Type](https://img.shields.io/badge/Type-Enterprise-purple?style=flat-square) |
| **ESGenius Benchmark** | [Paper](https://arxiv.org/html/2506.01646v1) | Evaluates 50 LLMs (0.5B to 671B params) on ESG knowledge in zero-shot and RAG setups. | ![Models](https://img.shields.io/badge/Models_Evaluated-50-blue?style=flat-square) |

---

## ⚖️ Regulatory & Compliance (RegTech)

> LLM and AI tools for AML, KYC, and regulatory compliance in financial services.

<p align="center">
  <img src="https://img.shields.io/badge/RegTech_Market-$14.94B_(2024)-blueviolet?style=flat-square" alt="Market Size"/>
  <img src="https://img.shields.io/badge/Projected-$106.92B_(2035)-success?style=flat-square" alt="Projected"/>
  <img src="https://img.shields.io/badge/CAGR-19.59%25-critical?style=flat-square" alt="CAGR"/>
  <img src="https://img.shields.io/badge/AI%2FML_Adoption-62%25_of_FIs-informational?style=flat-square" alt="Adoption"/>
</p>

| Company | Link | Description | Badges |
|---------|------|-------------|--------|
| **ComplyAdvantage** | [complyadvantage.com](https://complyadvantage.com/) | AI-driven risk management unifying screening, monitoring, and customer risk scoring. 75% reduction in manual compliance tasks. | ![Reduction](https://img.shields.io/badge/Manual_Tasks-−75%25-brightgreen?style=flat-square) |
| **Hawk AI** | [hawk.ai](https://hawk.ai/) | Transformer-based LLMs treating transactions as sentences. ~90% alert accuracy. Raised $56M Series C (2025). | ![Accuracy](https://img.shields.io/badge/Accuracy-~90%25-brightgreen?style=flat-square) ![Funding](https://img.shields.io/badge/Series_C-$56M-green?style=flat-square) |
| **Ascent RegTech** | [ascentregtech.com](https://www.ascentregtech.com/) | AI transforms regulations into actionable obligations. MiFID II in 2.5 min vs 1,800 hours manually. | ![Speed](https://img.shields.io/badge/Speed-43%2C200x_Faster-brightgreen?style=flat-square) |
| **Hummingbird** | [hummingbird.co](https://hummingbird.co/) | AML investigation platform from ex-Square, Stripe, and US Treasury experts. | ![Type](https://img.shields.io/badge/Type-AML-red?style=flat-square) |
| **Featurespace** | [featurespace.com](https://www.featurespace.com/) | ARIC Risk Hub for real-time payment fraud and AML detection using adaptive ML. | ![Type](https://img.shields.io/badge/Type-Fraud_%26_AML-red?style=flat-square) |
| **Flagright** | [flagright.com](https://www.flagright.com/) | Real-time AML compliance infrastructure with AI-powered transaction monitoring. | ![Type](https://img.shields.io/badge/Type-AML-red?style=flat-square) |
| **FINOS Open RegTech** | [finos/open-regtech-sig](https://github.com/finos/open-regtech-sig) | Community creating open-source solutions for regulatory and compliance issues in financial services. | ![Stars](https://img.shields.io/github/stars/finos/open-regtech-sig?style=flat-square&color=gold) |

---

## 🪙 Crypto, DeFi & Web3

> LLM-powered tools and agents for cryptocurrency, decentralized finance, and blockchain.

<p align="center">
  <img src="https://img.shields.io/badge/DeFAI_Market_Cap-$15.5B-gold?style=flat-square" alt="DeFAI Market"/>
  <img src="https://img.shields.io/badge/Q4_2024_Growth-+322%25-brightgreen?style=flat-square" alt="Growth"/>
</p>

| Tool | Link | Description | Badges |
|------|------|-------------|--------|
| **Virtuals Protocol** | [virtuals.io](https://www.virtuals.io/) | On-chain protocol for creating and co-owning AI agents via crypto tokens. Powers the DeFAI ecosystem. | ![FDV](https://img.shields.io/badge/AIXBT_FDV-$500M%2B-gold?style=flat-square) |
| **ChainGPT** | [chaingpt.org](https://www.chaingpt.org/) | Web3 AI infrastructure: Chatbot, Smart Contract Auditor, NFT Generator, Trading Assistant, no-code agent platform. | ![Type](https://img.shields.io/badge/Type-Web3_AI-blue?style=flat-square) |
| **Griffain** | [griffain.com](https://griffain.com/) | DeFAI platform on Solana. Agents for trades, wallet management, NFT minting via natural language. | ![Chain](https://img.shields.io/badge/Chain-Solana-purple?style=flat-square) |
| **Web3 AI Trading Agent** | [chainstacklabs/web3-ai-trading-agent](https://github.com/chainstacklabs/web3-ai-trading-agent) | Open-source autonomous trading agent for Uniswap V4 on BASE. Local LLMs + real-time data. | ![Stars](https://img.shields.io/github/stars/chainstacklabs/web3-ai-trading-agent?style=flat-square&color=gold) ![Chain](https://img.shields.io/badge/Chain-BASE-blue?style=flat-square) |
| **AlpacaTradingAgent** | [huygiatrng/AlpacaTradingAgent](https://github.com/huygiatrng/AlpacaTradingAgent) | Enhanced TradingAgents fork with real-time Alpaca integration, crypto support, and web interface. | ![Stars](https://img.shields.io/github/stars/huygiatrng/AlpacaTradingAgent?style=flat-square&color=gold) |
| **Fetch.ai / ASI Alliance** | [fetch.ai](https://fetch.ai/) | Combined AI-focused crypto networks (Fetch.ai + Ocean Protocol + SingularityNET) for decentralized autonomous economic agents. | ![Type](https://img.shields.io/badge/Type-Infrastructure-orange?style=flat-square) |

---

## 📦 Datasets

> Curated financial datasets for training, fine-tuning, and evaluating LLMs.

### Sentiment Analysis

| Dataset | Link | Description | Badges |
|---------|------|-------------|--------|
| **Financial PhraseBank** | [HuggingFace](https://huggingface.co/datasets/takala/financial_phrasebank) | 4,845 English sentences from financial news, annotated by 16 finance experts. The gold standard. | ![Samples](https://img.shields.io/badge/Samples-4%2C845-blue?style=flat-square) ![Annotators](https://img.shields.io/badge/Annotators-16_Experts-green?style=flat-square) |
| **FiQA** | [WWW 2018](https://sites.google.com/view/fiqa/) | Aspect-based sentiment from SeekingAlpha and financial forums. | ![Conference](https://img.shields.io/badge/WWW-2018-orange?style=flat-square) |
| **Twitter Financial News** | [HuggingFace](https://huggingface.co/datasets/zeroshot/twitter-financial-news-sentiment) | Financial news sentiment from Twitter for zero-shot/few-shot classification. | ![Type](https://img.shields.io/badge/Source-Twitter-blue?style=flat-square) |
| **SEntFiN 1.0** | [Paper](https://arxiv.org/abs/2305.12257) | 10,753 news headlines with entity-sentiment annotations, including multi-entity conflicts. | ![Samples](https://img.shields.io/badge/Samples-10%2C753-blue?style=flat-square) |
| **Kaggle Financial Sentiment** | [Kaggle](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news) | Publicly available financial news sentiment dataset. | ![Platform](https://img.shields.io/badge/Platform-Kaggle-20BEFF?style=flat-square) |

### Question Answering & Reasoning

| Dataset | Link | Description | Badges |
|---------|------|-------------|--------|
| **FinQA** | [GitHub](https://github.com/czyssrs/FinQA) | 8,281 expert-annotated QA pairs over financial reports requiring numerical reasoning. EMNLP 2021. | ![Samples](https://img.shields.io/badge/Samples-8%2C281-blue?style=flat-square) ![Paper](https://img.shields.io/badge/EMNLP-2021-purple?style=flat-square) |
| **TAT-QA** | [Project Page](https://nextplusplus.github.io/TAT-QA/) | 16,552 questions over hybrid tabular-textual contexts from real financial reports. | ![Samples](https://img.shields.io/badge/Questions-16%2C552-blue?style=flat-square) |
| **DocFinQA** | [Paper](https://arxiv.org/html/2401.06915v2) | 7,437 questions over full SEC filings (avg 123K words). Long-context financial reasoning benchmark. | ![Context](https://img.shields.io/badge/Avg_Context-123K_words-orange?style=flat-square) |
| **ConvFinQA** | [Related to FinQA](https://github.com/czyssrs/FinQA) | Multi-turn conversational financial QA simulating analyst-style questioning. | ![Type](https://img.shields.io/badge/Type-Conversational-blue?style=flat-square) |

### Named Entity Recognition

| Dataset | Link | Description | Badges |
|---------|------|-------------|--------|
| **FiNER-139** | [HuggingFace](https://huggingface.co/datasets/nlpaueb/finer-139) | 1.1M sentences annotated with 139 XBRL entity types from US public company reports. | ![Samples](https://img.shields.io/badge/Samples-1.1M-blue?style=flat-square) ![Entities](https://img.shields.io/badge/Entities-139_Types-green?style=flat-square) |

### Pre-Training Corpora

| Dataset | Link | Description | Badges |
|---------|------|-------------|--------|
| **FinPile (Bloomberg)** | [Paper](https://arxiv.org/abs/2303.17564) | 363B token corpus of English financial documents used to train BloombergGPT. | ![Tokens](https://img.shields.io/badge/Tokens-363B-blue?style=flat-square) ![Access](https://img.shields.io/badge/Access-Closed-red?style=flat-square) |
| **FIT (PIXIU)** | [GitHub](https://github.com/The-FinAI/PIXIU) | 136K instruction tuning samples spanning sentiment, stock prediction, and more. | ![Samples](https://img.shields.io/badge/Samples-136K-blue?style=flat-square) ![Access](https://img.shields.io/badge/Access-Open-brightgreen?style=flat-square) |
| **Finance-Alpaca** | [HuggingFace](https://huggingface.co/datasets/gbharti/finance-alpaca) | Finance-specific instruction tuning dataset. | ![Access](https://img.shields.io/badge/Access-Open-brightgreen?style=flat-square) |
| **SEC EDGAR Filings** | [SEC EDGAR](https://www.sec.gov/edgar) | 60,490 10-Ks and 142,622 10-Qs of Russell 3000 firms (1994-2019). | ![Coverage](https://img.shields.io/badge/Filings-200K%2B-blue?style=flat-square) ![Period](https://img.shields.io/badge/Period-1994--2019-orange?style=flat-square) |

### Curated Collections

| Collection | Link | Description |
|------------|------|-------------|
| **HuggingFace Finance Datasets** | [HuggingFace](https://huggingface.co/collections/sugatoray/llm-datasets-finance-66c2a291ef1f45cd71480e55) | Curated collection of financial LLM datasets on HuggingFace. |
| **financial-datasets (Python lib)** | [virattt/financial-datasets](https://github.com/virattt/financial-datasets) | Open-source library to create Q&A datasets from 10-K, 10-Q, PDFs for LLM training. |

---

## 🏆 Benchmarks & Evaluation

> Standardized benchmarks for evaluating LLM performance on financial tasks.

| Benchmark | Link | Description | Badges |
|-----------|------|-------------|--------|
| **FinBen** | [NeurIPS 2024](https://github.com/The-FinAI/finben) | The most comprehensive financial benchmark. 42 datasets, 24 tasks, 8 evaluation categories. | ![Datasets](https://img.shields.io/badge/Datasets-42-blue?style=flat-square) ![Tasks](https://img.shields.io/badge/Tasks-24-green?style=flat-square) ![Paper](https://img.shields.io/badge/NeurIPS-2024-purple?style=flat-square) |
| **FLUE** | [SALT-NLP](https://salt-nlp.github.io/FLANG/) | First comprehensive financial NLP benchmark. 5 tasks: sentiment, headlines, NER, structure, QA. | ![Tasks](https://img.shields.io/badge/Tasks-5-blue?style=flat-square) ![Paper](https://img.shields.io/badge/arXiv-2211.00083-b31b1b?style=flat-square&logo=arxiv) |
| **Open FinLLM Leaderboard** | [HuggingFace Space](https://huggingface.co/spaces/finosfoundation/Open-Financial-LLM-Leaderboard) | FINOS + HuggingFace live leaderboard. Transparent, standardized LLM ranking across financial tasks. | ![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square) ![Org](https://img.shields.io/badge/FINOS-Linux_Foundation-blue?style=flat-square) |
| **PIXIU** | [GitHub](https://github.com/The-FinAI/PIXIU) | Full framework: FinMA model + FIT data + FinBen evaluation. | ![Paper](https://img.shields.io/badge/NeurIPS-2023-purple?style=flat-square) |
| **FinMTEB** | [HuggingFace Space](https://huggingface.co/spaces/FinanceMTEB/FinMTEB) | Financial Massive Text Embedding Benchmark in English and Chinese. | ![Languages](https://img.shields.io/badge/Languages-EN_%26_ZH-blue?style=flat-square) |
| **FLAME** | [ACL 2025](https://aclanthology.org/2025.gem-1.72.pdf) | Financial language model evaluation benchmark at ACL 2025. | ![Paper](https://img.shields.io/badge/ACL-2025-orange?style=flat-square) |
| **Golden Touchstone** | [Paper](https://arxiv.org/html/2411.06272) | Bilingual benchmark covering 8 core financial NLP tasks (Chinese/English). | ![Tasks](https://img.shields.io/badge/Tasks-8-blue?style=flat-square) ![Languages](https://img.shields.io/badge/Bilingual-ZH_%26_EN-blue?style=flat-square) |
| **FinEval** | [Paper](https://arxiv.org/abs/2308.09975) | Chinese financial domain knowledge evaluation benchmark. | ![Language](https://img.shields.io/badge/Language-Chinese-red?style=flat-square) |

---

## 📄 Research Papers

> Key research papers advancing the field of LLMs in finance.

### Survey Papers

| Paper | Year | Link | Badges |
|-------|------|------|--------|
| **Large Language Models in Finance: A Survey** | 2023 | [arXiv:2311.10723](https://arxiv.org/abs/2311.10723) | ![Paper](https://img.shields.io/badge/arXiv-2311.10723-b31b1b?style=flat-square&logo=arxiv) |
| **A Survey of Large Language Models in Finance (FinLLMs)** | 2024 | [arXiv:2402.02315](https://arxiv.org/abs/2402.02315) | ![Paper](https://img.shields.io/badge/arXiv-2402.02315-b31b1b?style=flat-square&logo=arxiv) |
| **A Survey of LLMs for Financial Applications** | 2024 | [arXiv:2406.11903](https://arxiv.org/abs/2406.11903) | ![Paper](https://img.shields.io/badge/arXiv-2406.11903-b31b1b?style=flat-square&logo=arxiv) |
| **LLM Agent in Financial Trading: A Survey** | 2024 | [arXiv:2408.06361](https://arxiv.org/abs/2408.06361) | ![Paper](https://img.shields.io/badge/arXiv-2408.06361-b31b1b?style=flat-square&logo=arxiv) |
| **The New Quant: LLMs in Financial Prediction and Trading** | 2025 | [arXiv:2510.05533](https://arxiv.org/html/2510.05533v1) | ![Paper](https://img.shields.io/badge/arXiv-2510.05533-b31b1b?style=flat-square&logo=arxiv) |

### Foundational Model Papers

| Paper | Year | Link | Badges |
|-------|------|------|--------|
| **BloombergGPT: A Large Language Model for Finance** | 2023 | [arXiv:2303.17564](https://arxiv.org/abs/2303.17564) | ![Params](https://img.shields.io/badge/Params-50B-blue?style=flat-square) ![Tokens](https://img.shields.io/badge/Tokens-363B-green?style=flat-square) |
| **FinGPT: Open-Source Financial Large Language Models** | 2023 | [arXiv:2306.06031](https://arxiv.org/abs/2306.06031) | ![Cost](https://img.shields.io/badge/Fine--tune_Cost-<$300-brightgreen?style=flat-square) |
| **FinBERT: Financial Sentiment Analysis with Pre-trained Language Models** | 2019 | [arXiv:1908.10063](https://arxiv.org/abs/1908.10063) | ![Accuracy](https://img.shields.io/badge/Accuracy-97%25-brightgreen?style=flat-square) |
| **PIXIU: A Large Language Model, Instruction Data and Evaluation Benchmark for Finance** | 2023 | [arXiv:2306.05443](https://arxiv.org/abs/2306.05443) | ![Paper](https://img.shields.io/badge/NeurIPS-2023-purple?style=flat-square) |
| **InvestLM: Investment using Financial Domain Instruction Tuning** | 2023 | [arXiv:2309.13064](https://arxiv.org/abs/2309.13064) | ![Base](https://img.shields.io/badge/Base-LLaMA--65B-blue?style=flat-square) |
| **FinTral: GPT-4 Level Multimodal Financial LLMs** | 2024 | [arXiv:2402.10986](https://arxiv.org/abs/2402.10986) | ![Base](https://img.shields.io/badge/Base-Mistral--7B-blue?style=flat-square) |
| **FinQA: Numerical Reasoning over Financial Data** | 2021 | [arXiv:2109.00122](https://arxiv.org/abs/2109.00122) | ![Paper](https://img.shields.io/badge/EMNLP-2021-purple?style=flat-square) |
| **FLUE & FLANG: Benchmarks for Financial Domain** | 2022 | [arXiv:2211.00083](https://arxiv.org/abs/2211.00083) | ![Paper](https://img.shields.io/badge/arXiv-2211.00083-b31b1b?style=flat-square&logo=arxiv) |
| **Open FinLLM Leaderboard** | 2025 | [arXiv:2501.10963](https://arxiv.org/abs/2501.10963) | ![Org](https://img.shields.io/badge/FINOS-Linux_Foundation-blue?style=flat-square) |

---

## 🔧 Fine-Tuning & Adaptation

> Tools and techniques for adapting LLMs to financial domains.

| Tool | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **FinGPT Fine-Tuning** | [AI4Finance-Foundation/FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | Full training/fine-tuning pipelines. LoRA fine-tuning on news and tweets sentiment. Cost under $300. | ![Cost](https://img.shields.io/badge/Cost-<$300-brightgreen?style=flat-square) |
| **FinLoRA** | [Open-Finance-Lab/FinLoRA](https://github.com/Open-Finance-Lab/FinLoRA) | Benchmarks LoRA methods (LoRA, QLoRA, DoRA, rsLoRA) on 19 financial datasets including 4 novel XBRL datasets. +36.4% to +67.1% gains. | ![Stars](https://img.shields.io/github/stars/Open-Finance-Lab/FinLoRA?style=flat-square&color=gold) ![Gain](https://img.shields.io/badge/Gain-+36%25_to_+67%25-brightgreen?style=flat-square) ![Params](https://img.shields.io/badge/Trainable-0.01%25-blue?style=flat-square) |
| **FinNLP** | [AI4Finance-Foundation/FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | Democratizing internet-scale financial data. Full pipelines for LLM training and fine-tuning in finance. | ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinNLP?style=flat-square&color=gold) |
| **LLM Open Finance Models** | [HuggingFace Blog](https://huggingface.co/blog/DragonLLM/llm-open-finance-models) | AGEFI + Dragon LLM initiative. 8B-parameter models specialized for financial language (EN + FR). | ![Params](https://img.shields.io/badge/Params-8B-blue?style=flat-square) ![Languages](https://img.shields.io/badge/Languages-EN_%26_FR-blue?style=flat-square) |

---

## 🔌 APIs & Data Platforms

> APIs and platforms providing financial data optimized for LLM consumption.

| Platform | Link | Description | Badges |
|----------|------|-------------|--------|
| **Kensho LLM-ready API** | [llmreadyapi.kensho.com](https://llmreadyapi.kensho.com/) | S&P Global's API for LLMs to query Capital IQ, Compustat, and Market Data via natural language. | ![Org](https://img.shields.io/badge/S%26P-Global-blue?style=flat-square) ![Year](https://img.shields.io/badge/Launched-2024-green?style=flat-square) |
| **Alpha Vantage** | [alphavantage.co](https://www.alphavantage.co/) | Real-time/historical data for 200K+ tickers across 20+ exchanges. News & Sentiments API with LLM-based sentiment signals. | ![Tickers](https://img.shields.io/badge/Tickers-200K%2B-blue?style=flat-square) |
| **Polygon.io** | [polygon.io](https://polygon.io/) | Normalized market data API for dashboards, financial reporting, and historical analytics. | ![Type](https://img.shields.io/badge/Type-Market_Data-blue?style=flat-square) |
| **Financial Datasets** | [financialdatasets.ai](https://www.financialdatasets.ai/) | 30K+ tickers over 30+ years: financial statements, equity prices, insider trades, SEC filings. | ![Coverage](https://img.shields.io/badge/History-30%2B_Years-blue?style=flat-square) |
| **Finnhub** | [finnhub.io](https://finnhub.io/) | Institutional-grade data with the most generous free tier (60 calls/min). Real-time prices, fundamentals, alternative data. | ![Free](https://img.shields.io/badge/Free_Tier-60_calls%2Fmin-brightgreen?style=flat-square) |
| **Intrinio** | [intrinio.com](https://intrinio.com/) | Extensive coverage: stocks, options, ETFs, mutual funds, ESG data, SEC filings. Built for fintech developers. | ![Type](https://img.shields.io/badge/Type-Multi--Asset-blue?style=flat-square) |
| **Nasdaq Data Link** | [data.nasdaq.com](https://data.nasdaq.com/) | 20M+ indicators from 250+ sources. Premium datasets including ESG scores and alternative data. | ![Indicators](https://img.shields.io/badge/Indicators-20M%2B-blue?style=flat-square) |
| **LLMQuant Data** | [data.llmquant.com](https://data.llmquant.com/) | Finance Data API specifically designed for LLM-powered quantitative research. | ![Type](https://img.shields.io/badge/Type-LLM_Optimized-purple?style=flat-square) |
| **QuantConnect MCP** | [quantconnect.com/mcp](https://www.quantconnect.com/mcp) | MCP server bridging LLMs to algorithmic trading API via natural language. | ![Type](https://img.shields.io/badge/Type-MCP_Server-orange?style=flat-square) |

---

## 🎓 Courses & Tutorials

> Educational resources for learning about LLMs in finance.

### University & Executive Programs

| Course | Institution | Link | Badges |
|--------|------------|------|--------|
| **Machine Learning for Finance** | University of Chicago | [UChicago](https://online.professional.uchicago.edu/course/machine-learning-for-finance/) | ![Duration](https://img.shields.io/badge/Duration-8_Weeks-blue?style=flat-square) |
| **SoFiE Financial ML Summer School** | Yale School of Management | [Yale](https://som.yale.edu/sofie-financial-machine-learning-summer-school) | ![Institution](https://img.shields.io/badge/Yale-SoM-blue?style=flat-square) |
| **ML & AI in Finance** | HEC Paris | [HEC](https://www.hec.edu/en/executive-education/machine-learning-ai-finance) | ![Type](https://img.shields.io/badge/Type-Executive-purple?style=flat-square) |
| **ML in Finance** | NYU SPS | [NYU](https://www.sps.nyu.edu/courses/FINA1-CE9315-machine-learning-in-finance.html) | ![Institution](https://img.shields.io/badge/NYU-SPS-violet?style=flat-square) |
| **CS224N: NLP with Deep Learning** | Stanford | [Stanford](https://web.stanford.edu/class/cs224n/) | ![Foundation](https://img.shields.io/badge/Foundation-NLP-green?style=flat-square) |

### Online Courses (MOOCs)

| Course | Platform | Link | Badges |
|--------|----------|------|--------|
| **Introduction to Generative AI in Finance** | Coursera | [Coursera](https://www.coursera.org/learn/introduction-to-generative-ai-in-finance) | ![Platform](https://img.shields.io/badge/Coursera-blue?style=flat-square&logo=coursera) |
| **Generative AI in Finance** | Coursera | [Coursera](https://www.coursera.org/learn/generative-ai-in-finance) | ![Platform](https://img.shields.io/badge/Coursera-blue?style=flat-square&logo=coursera) |
| **AI Fundamentals in Financial Services** | Coursera | [Coursera](https://www.coursera.org/learn/ai-financial-services) | ![Platform](https://img.shields.io/badge/Coursera-blue?style=flat-square&logo=coursera) |
| **AI for Finance Specialization** | Coursera | [Coursera](https://www.coursera.org/specializations/ai-for-finance) | ![Type](https://img.shields.io/badge/Type-Specialization-orange?style=flat-square) |
| **ML & RL in Finance** | Coursera (NYU) | [Coursera](https://www.coursera.org/specializations/machine-learning-reinforcement-finance) | ![Type](https://img.shields.io/badge/Type-Specialization-orange?style=flat-square) |
| **Generative AI for Finance Analysts** | Udemy | [Udemy](https://www.udemy.com/course/generative-ai-for-finance-analysts/) | ![Platform](https://img.shields.io/badge/Udemy-purple?style=flat-square&logo=udemy) |
| **AI for Finance: ML & DL for Trading** | Udemy | [Udemy](https://www.udemy.com/course/ai-for-finance-machine-learning-deep-learning-for-trading/) | ![Platform](https://img.shields.io/badge/Udemy-purple?style=flat-square&logo=udemy) |

### GitHub Learning Resources

| Resource | Repository | Description | Badges |
|----------|-----------|-------------|--------|
| **LLMs-in-Finance (Notebooks)** | [hananedupouy/LLMs-in-Finance](https://github.com/hananedupouy/LLMs-in-Finance) | Hands-on Jupyter notebooks with OpenAI Agents SDK, Claude, AutoGen, LlamaIndex, CrewAI for finance. | ![Stars](https://img.shields.io/github/stars/hananedupouy/LLMs-in-Finance?style=flat-square&color=gold) |
| **FinNLP-Progress** | [YangLinyi/FinNLP-Progress](https://github.com/YangLinyi/FinNLP-Progress) | Tracks NLP progress in finance: datasets, papers, and SOTA results. | ![Stars](https://img.shields.io/github/stars/YangLinyi/FinNLP-Progress?style=flat-square&color=gold) |
| **finllm-apps** | [tinztwins/finllm-apps](https://github.com/tinztwins/finllm-apps) | Collection of LLM apps in finance using RAG and AI agents with open-source models. | ![Stars](https://img.shields.io/github/stars/tinztwins/finllm-apps?style=flat-square&color=gold) |

---

## 🏢 Companies & Startups

> Notable companies and startups at the intersection of LLMs and finance.

| Company | Link | Description | Badges |
|---------|------|-------------|--------|
| **AlphaSense** | [alpha-sense.com](https://www.alpha-sense.com/) | AI-powered market intelligence. $400M+ ARR, 88% of S&P 100 as clients. CNBC Disruptor 50 (2025). | ![ARR](https://img.shields.io/badge/ARR-$400M%2B-green?style=flat-square) ![Clients](https://img.shields.io/badge/Clients-88%25_S%26P_100-blue?style=flat-square) |
| **Kensho (S&P Global)** | [kensho.com](https://www.kensho.com/) | Acquired by S&P Global for $550M. LLM-ready API for financial data queries. | ![Acquired](https://img.shields.io/badge/Acquired-$550M-green?style=flat-square) |
| **Numerai** | [numer.ai](https://numer.ai/) | AI-powered crowdsourced hedge fund. AUM ~$550M, 25.45% net return in 2024. Raised $30M in 2025. | ![AUM](https://img.shields.io/badge/AUM-~$550M-blue?style=flat-square) ![Returns](https://img.shields.io/badge/2024_Returns-25.45%25-brightgreen?style=flat-square) |
| **Alpaca** | [alpaca.markets](https://alpaca.markets/) | Developer-first, commission-free API brokerage for algorithmic and AI-driven trading. | ![Type](https://img.shields.io/badge/Type-API_Brokerage-blue?style=flat-square) |
| **Dataminr** | [dataminr.com](https://www.dataminr.com/) | AI platform for real-time event detection across 160+ languages. Originally built for trading floors. | ![Languages](https://img.shields.io/badge/Languages-160%2B-blue?style=flat-square) |
| **AI4Finance Foundation** | [ai4finance.org](https://ai4finance.org/) | Open-source org behind FinGPT, FinRL, FinRobot, FinRL-Meta. The ecosystem for open-source financial AI. | ![Type](https://img.shields.io/badge/Type-Open_Source-brightgreen?style=flat-square) |
| **DDScore** | [ddscore.ai](https://www.ddscore.ai/) | AI-assisted first-pass due diligence that compares private-company materials with each other and with public sources. | ![Type](https://img.shields.io/badge/Type-Due_Diligence-blue?style=flat-square) |

---

## 💬 Prompt Engineering for Finance

> Techniques and resources for effective financial prompt design.

| Resource | Repository | Description | Badges |
|----------|-----------|-------------|--------|
| **prompteng-finance** | [sciencenerd880/prompteng-finance](https://github.com/sciencenerd880/prompteng-finance) | Explores zero-shot, few-shot, and chain-of-thought prompting for financial sentiment analysis via Groq API. | ![Stars](https://img.shields.io/github/stars/sciencenerd880/prompteng-finance?style=flat-square&color=gold) |
| **GPT for Financial Advice** | [HSLU-IFZ/GPT_for_Financial_Advice](https://github.com/HSLU-IFZ-Competence-Center-Investments/GPT_for_Financial_Advice) | Research using GPT-3.5-turbo with prompt engineering for financial advice generation. | ![Stars](https://img.shields.io/github/stars/HSLU-IFZ-Competence-Center-Investments/GPT_for_Financial_Advice?style=flat-square&color=gold) |
| **ChatGPT Financial Advisor** | [jiaton/ChatGPT-Financial-Advisor](https://github.com/jiaton/ChatGPT-Financial-Advisor) | ChatGPT-based financial advisor implementation with optimized prompts. | ![Stars](https://img.shields.io/github/stars/jiaton/ChatGPT-Financial-Advisor?style=flat-square&color=gold) |

---

## 📋 Related Awesome Lists

> Other curated lists at the intersection of AI and finance.

| List | Repository | Description | Badges |
|------|-----------|-------------|--------|
| **awesome-quant** | [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) | The most starred finance resource list on GitHub. Libraries, packages, and resources for Quants. | ![Stars](https://img.shields.io/github/stars/wilsonfreitas/awesome-quant?style=flat-square&color=gold) |
| **awesome-ai-in-finance** | [georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance) | Curated list of LLMs and deep learning strategies in financial markets. | ![Stars](https://img.shields.io/github/stars/georgezouq/awesome-ai-in-finance?style=flat-square&color=gold) |
| **Awesome-FinLLMs** | [DataArcTech/Awesome-FinLLMs](https://github.com/DataArcTech/Awesome-FinLLMs) | Curated list of financial LLMs: papers, models, datasets, codebases. Bilingual (EN/ZH). | ![Stars](https://img.shields.io/github/stars/DataArcTech/Awesome-FinLLMs?style=flat-square&color=gold) |
| **Finance-LLMs** | [kennethleungty/Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs) | Real-world LLM implementations in financial services. | ![Stars](https://img.shields.io/github/stars/kennethleungty/Finance-LLMs?style=flat-square&color=gold) |
| **FinLLMs (Survey)** | [adlnlp/FinLLMs](https://github.com/adlnlp/FinLLMs) | Companion repo for "Large Language Models in Finance" survey. Neural Computing and Applications 2025. | ![Stars](https://img.shields.io/github/stars/adlnlp/FinLLMs?style=flat-square&color=gold) |
| **awesome-financial-nlp** | [icoxfog417/awesome-financial-nlp](https://github.com/icoxfog417/awesome-financial-nlp) | NLP research resources for the financial domain. | ![Stars](https://img.shields.io/github/stars/icoxfog417/awesome-financial-nlp?style=flat-square&color=gold) |
| **financial-machine-learning** | [firmai/financial-machine-learning](https://github.com/firmai/financial-machine-learning) | Practical financial ML tools and applications. | ![Stars](https://img.shields.io/github/stars/firmai/financial-machine-learning?style=flat-square&color=gold) |
| **LLM_X_papers** | [czyssrs/LLM_X_papers](https://github.com/czyssrs/LLM_X_papers) | Continually-updated reading list of LLM papers in Finance, Healthcare, and Law. | ![Stars](https://img.shields.io/github/stars/czyssrs/LLM_X_papers?style=flat-square&color=gold) |

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Guidelines

1. Make sure the resource is related to LLMs and Finance
2. Add new entries to the appropriate category
3. Follow the existing format with badges
4. Include a brief but informative description
5. Verify all links are working

---

## Authors

<table>
  <tr>
    <td align="center">
      <strong>Simon-Pierre Boucher</strong><br/>
      <a href="https://www.spboucher.ai">www.spboucher.ai</a><br/>
      <a href="mailto:spbou4@protonmail.com">spbou4@protonmail.com</a><br/><br/>
      <a href="https://www.spboucher.ai"><img src="https://img.shields.io/badge/Website-spboucher.ai-blue?style=flat-square&logo=google-chrome&logoColor=white" alt="Website"/></a>
      <a href="mailto:spbou4@protonmail.com"><img src="https://img.shields.io/badge/Email-ProtonMail-8B89CC?style=flat-square&logo=protonmail&logoColor=white" alt="Email"/></a>
    </td>
    <td align="center">
      <strong>Claude (Anthropic)</strong><br/>
      AI Research Assistant<br/><br/>
      <a href="https://www.anthropic.com"><img src="https://img.shields.io/badge/Anthropic-Claude-blueviolet?style=flat-square" alt="Claude"/></a>
    </td>
  </tr>
</table>

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <img src="https://img.shields.io/badge/⭐_Star_this_repo_if_you_find_it_useful!-gold?style=for-the-badge" alt="Star"/>
</p>

<p align="center">
  <sub>Built with ❤️ for the finance and AI community</sub>
</p>
