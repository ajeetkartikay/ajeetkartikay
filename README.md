<h1 align="center">Hi, I'm Ajeet Kumar</h1>

<p align="center">
  Machine Learning Engineer · AI Systems · Reinforcement Learning · NLP<br>
  Computer Science undergrad at IIIT Kottayam, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ajeet-kumar-636133345"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:ajeetkartikay96@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/ajeetkartikay"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://huggingface.co/kartik1230"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"></a>
</p>

---

## About Me

I like building things end to end, from training a model to deploying it, and lately also going lower in the stack to see how code actually runs on the machine.

- Grand Finalist at the Meta × Scaler OpenEnv Hackathon (52,000+ participants)
- Working on multi-agent RL environments where small LLMs learn to route work across specialists
- Previously built cross-lingual RAG (English, Hindi, Kannada, Malayalam), agent-based systems and ESG analytics
- 2nd Runner-up at Hackzilla National Hackathon (IIIT Sonepat)
- 200+ DSA problems solved, CGPA 7.8

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**LLM / NLP / Retrieval**

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

**Backend & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Cloud & Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Projects

### [minic: a compiler from scratch in C++](https://github.com/ajeetkartikay/minic)

A small compiler for a toy imperative language. It reads source code, builds an AST, runs a few optimisations and writes out x86-64 assembly, which GCC turns into a normal Linux executable. No parser generators and no LLVM, just plain C++17.

- Hand-written lexer and recursive-descent parser, with operator precedence handled in the grammar
- A semantic check for undeclared variables, redeclarations and scope errors, with line numbers in the error messages
- Constant folding, algebraic simplification and dead-branch removal, careful not to fold away things like division by zero
- Code generation that follows the System V calling convention, so the output can call `printf` directly
- Tests run every program at `-O0` and `-O1` and check the outputs match

Stack: C++17, x86-64 assembly, GCC, Linux, Make

---

### [AutoDataLab++: multi-agent OpenEnv RL environment](https://github.com/ajeetkartikay/AutoDataLab-meta)

A multi-agent environment where a Chief of Staff agent routes work across four specialists (Data Analyst, Finance, Strategy, HR) to complete CEO briefing tasks. The policy is a GRPO-trained Qwen2.5-1.5B, with optional RAG over company memory.

My part: the HR/Communications sub-environment and its grader (45% structure, 45% tone, 10% audience), deployment to HF Spaces with Docker and Git LFS, the validation setup (live HTTP smoke tests, GitHub Actions CI, session capping), and the README and write-up.

[Live demo](https://kartik1230-round2-1.hf.space/ui/) · [Blog](https://github.com/ajeetkartikay/AutoDataLab-meta/blob/main/Blog.md)

Grand Finalist (Round 2), Meta × Scaler OpenEnv Hackathon

---

### [Aerial GCP pose estimation (Skylark Drones assignment)](https://github.com/ajeetkartikay/Skylark_Drones_Assignment)

A multi-task computer vision model for drone images. From one ResNet-50 backbone it predicts where the Ground Control Point marker is, down to the pixel, and what shape it is (cross, square or L-shaped).

- Started with direct coordinate regression, then switched to Gaussian heatmaps with soft-argmax decoding, which improved PCK@25 by more than 40×
- Found and fixed a zero-gradient bug by training both heads together with MSE + cross-entropy loss; shape classification reached 100% validation macro F1
- Made training workable on CPU by freezing the backbone and warm-starting from earlier checkpoints
- Deployed an inference demo on Hugging Face Spaces

Stack: Python, PyTorch, ResNet-50, OpenCV, Hugging Face Spaces, Docker

[Live demo](https://huggingface.co/spaces/Ajeetkartik/skylark-gcp-pose-estimation-multitask)

---

### [Multilingual retrieval-augmented QA](https://github.com/ajeetkartikay/multilingual-rag-msr)

Question answering across English, Hindi, Kannada and Malayalam using multilingual sentence embeddings and FAISS for retrieval. Answers are extracted from the retrieved text, and the whole pipeline runs fine on a CPU.

Stack: Python, Sentence-Transformers, FAISS

---

### [AI agent system](https://github.com/ajeetkartikay)

An LLM-based multi-agent setup with supervisor, search, chat and worker agents that handle intent routing, retrieval and API calls. It uses RAG with Pinecone for context, and conversation memory so it can carry out multi-step things like search followed by booking.

Stack: FastAPI, LangChain, Gemini API, Pinecone

---

## What I'm working on

- RL for LLM agents: reward design, OpenEnv, multi-agent setups
- Making RAG systems more reliable: retrieval evaluation, hybrid search, grounded citations
- Systems and compilers in C++
- Looking for ML / AI engineering and systems roles

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ajeetkartikay&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="170">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ajeetkartikay&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="170">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ajeetkartikay&theme=tokyonight&hide_border=true" height="170">
</p>
