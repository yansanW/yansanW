# Hi, I'm Woo Yan San 👋

AI / Machine Learning Engineer with a PhD in Computer Science & Engineering.

I build intelligent systems that turn messy real-world information into useful outputs, with experience across:

- Computer Vision
- 3D Vision & Reconstruction
- Edge / On-device ML
- Applied Machine Learning
- RAG & GenAI systems
- Agentic AI workflows

My strongest technical background is in Computer Vision and 3D reconstruction, with newer hands-on work in RAG, LLM applications, and agentic AI systems.

---

## 🔬 Core Technical Areas

**Computer Vision & Machine Learning**  
Python · PyTorch · scikit-learn · YOLO · Object Detection · Regression · Feature Engineering · Model Evaluation

**3D Vision**  
Multi-view Geometry · COLMAP / SfM · Triangulation · Differentiable Rendering · Semantic 3D Gaussian Representations

**Edge AI**  
TensorFlow Lite · Model Optimization · Quantization · On-device Inference · Mobile Deployment

**GenAI & RAG**  
LangChain · Embeddings · ChromaDB · Conversational Retrieval · Query Rewriting · Reranking · RAGAS Evaluation

**AI Backend / Agentic Systems**  
FastAPI · Pydantic · Docker · Local / Cloud LLMs · Routing · Structured Outputs · Agentic Workflows

**Previous Engineering Background**  
FPGA · VHDL · RTL Design · Digital Logic · Hardware Debugging

---

## 🍇 Computer Vision & Edge AI — Tsubura

**Tsubura** is a publicly released smartphone application for AI-assisted grape berry counting.

I owned the ML development across data preparation, model experimentation, evaluation, mobile optimization, and retraining from field feedback.

Earlier work underlying the system achieved:

- **MAE 2.60**
- **~0.33 s/image** on Sony Xperia 1 III
- fully offline mobile inference

📱 [Tsubura](https://vc.media.yamanashi.ac.jp/tsubura/?lang=en)  
🔬 [Smart Agriculture Research](https://vc.media.yamanashi.ac.jp/research-smartagri/?lang=en)

The project was covered by NHK, Nikkei, Yomiuri Shimbun, and other Japanese media.

---

## 3D Computer Vision

My PhD research focused on reconstructing explicit semantic 3D grape-bunch models from ordinary multi-view field imagery.

The work progressed from:

**COLMAP point clouds + clustering**

to:

**geometry-aware correspondence → triangulation → semantic 3D Gaussian initialization → differentiable refinement**

Final-stage refinement improved:

- **OBB-IoU F1: 35.6% → 88.5%** at τ = 0.10
- **OBB-IoU F1: 10.3% → 74.9%** at τ = 0.25
- berry-count MAE: **3.7 → 2.5**

---

## GenAI & RAG

I have been expanding into GenAI through progressively more complete projects:

### Minimum RAG Chatbot
Conversational PDF RAG system with:

- embeddings + vector retrieval
- ChromaDB
- history-aware query rewriting
- Cohere reranking
- conversational context
- RAGAS evaluation

### Enterprise Agentic RAG
A modular, headless RAG backend exploring:

- cloud and local LLM inference
- query routing
- conversational rewriting
- semantic chunking
- structured Pydantic outputs
- RAGAS evaluation
- FastAPI
- Docker
- persistent sessions
- agentic workflow patterns

---

## Current Direction

Currently building deeper practical experience in:

**AI Engineering · RAG · Agentic AI · Multimodal AI · Computer Vision · Mobile Apps Development**

I am particularly interested in systems where model capability, engineering constraints, evaluation, and real-world usefulness all matter.
