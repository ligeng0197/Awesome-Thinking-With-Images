# Awesome-Thinking-With-Images

<p align="center">
  <img src="assets/image.png" width="100%">
</p>

A **curated** list of research methods and datasets exploring **image thinking** — the ability to perform reasoning with images. We focus particularly on methods and benchmarks designed for **fine-grained visual understanding** tasks, which refers to problems with **Dense, Cluttered, Complex Visual Input**, but only **Tiny, Subtle, Ambiguous Visual Regions Subsets** are useful for answering.

This includes:
- Multimodal reasoning with visual context  
- Visual chain-of-thought prompting  
- Dynamic visual attention / focus adjustment  
- Vision-language models with interpretable intermediate states

Feel free to contribute! Pull requests and issues recommendation are welcome.

---

## 📚 Awesome Papers

### 🔹 Training-Free / No-Training Methods

| Paper | Venue | Date | Resources |
|-------|-------|------|-----------|
| ![Star](https://img.shields.io/github/stars/THUNLP-MT/VAT.svg?style=social&label=Star) <br> [**Visual Abstract Thinking Empowers Multimodal Reasoning**](https://arxiv.org/abs/2505.20164) | arXiv | 2025-05 | [GitHub](https://github.com/THUNLP-MT/VAT) |
| ![Star](https://img.shields.io/github/stars/PKU-ICST-MIPL/DyFo_CVPR2025.svg?style=social&label=Star) <br> [**DyFo: A Training-Free Dynamic Focus Visual Search for Enhancing LMMs in Fine-Grained Visual Understanding**](https://arxiv.org/abs/2504.14920) | CVPR Highlight | 2025-04 | [GitHub](https://github.com/PKU-ICST-MIPL/DyFo_CVPR2025) |
| ![Star](https://img.shields.io/github/stars/dreammr/rap.svg?style=social&label=Star) <br> [**Retrieval-Augmented Perception: High-Resolution Image Perception Meets Visual RAG**](https://arxiv.org/abs/2503.01222) | ICML | 2025-03 | [GitHub](https://github.com/dreammr/rap) |
| ![Star](https://img.shields.io/github/stars/om-ai-lab/ZoomEye.svg?style=social&label=Star) <br> [**ZoomEye: Enhancing Multimodal LLMs with Human-Like Zooming Capabilities through Tree-Based Image Exploration**](https://arxiv.org/abs/2411.16044) | arXiv | 2024-11 | [GitHub](https://github.com/om-ai-lab/ZoomEye) |


---

### 🔹 Supervised Fine-tuning Methods

| Paper | Venue | Date | Resources |
|-------|-------|------|-----------|
| ![Star](https://img.shields.io/github/stars/steven-ccq/VisualReasoner.svg?style=social&label=Star) <br> [**From the Least to the Most: Building a Plug-and-Play Visual Reasoner via Data Synthesis**](https://arxiv.org/abs/2406.19934) | arXiv | 2024-06 | [GitHub](https://github.com/steven-ccq/VisualReasoner) |
| ![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star) <br> [**V\*: Guided Visual Search as a Core Mechanism in Multimodal LLMs**](https://arxiv.org/abs/2312.14135) | CVPR | 2023-12 | [GitHub](https://github.com/penghao-wu/vstar) |


---

### 🔹 RL-Enhanced Methods

| Paper | Venue | Date | Resources |
|-------|-------|------|-----------|
| ![Star](https://img.shields.io/github/stars/AntResearchNLP/ViLaSR.svg?style=social&label=Star) <br> [**Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing**](https://arxiv.org/abs/2506.09965) | arXiv | 2025-06 | [GitHub](https://github.com/AntResearchNLP/ViLaSR) |
| ![Star](https://img.shields.io/github/stars/None/None.svg?style=social&label=Star) <br> [**VLM-R: Region Recognition, Reasoning, and Refinement for Enhanced Multimodal Chain-of-Thought**](https://arxiv.org/abs/2505.16192) | arXiv | 2025-05 | N/A |
| ![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/Pixel-Reasoner.svg?style=social&label=Star) <br> [**Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning**](https://arxiv.org/abs/2505.15966) | arXiv | 2025-05 | [GitHub](https://github.com/TIGER-AI-Lab/Pixel-Reasoner) |
| ![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyes.svg?style=social&label=Star) <br> [**DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning**](https://arxiv.org/abs/2505.14362) | arXiv | 2025-05 | [GitHub](https://github.com/Visual-Agent/DeepEyes) |
| ![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-ARFT.svg?style=social&label=Star) <br> [**Visual Agentic Reinforcement Fine-Tuning (Visual-ARFT)**](https://arxiv.org/abs/2505.14246) | arXiv | 2025-05 | [GitHub](https://github.com/Liuziyu77/Visual-RFT/tree/main/Visual-ARFT) |
| ![Star](https://img.shields.io/github/stars/zhaochen0110/OpenThinkIMG.svg?style=social&label=Star) <br> [**OpenThinkIMG: Learning to Think with Images via Visual Tool Reinforcement Learning**](https://arxiv.org/abs/2505.08617) | arXiv | 2025-05 | [GitHub](https://github.com/zhaochen0110/OpenThinkIMG) |






---

## 🧪 Benchmarks & Datasets

| Dataset | Task | Resources |
|-------|-------|-----------|
| [**V\***](https://huggingface.co/datasets/craigwu/vstar_bench) | Attribute Recognition & Spatial Reasoning | [HuggingFace](https://huggingface.co/datasets/craigwu/vstar_bench) |
| [**HR-Bench**](https://huggingface.co/datasets/DreamMr/HR-Bench) | Fine-grained Single/Cross-instance Perception | [HuggingFace](https://huggingface.co/datasets/DreamMr/HR-Bench) |


---

## 🤝 Contributing

If you know any relevant papers, datasets, or demos, feel free to submit a pull request or leava an issue!

---

## 🔍 Related Lists

- [Awesome Multimodal LLMs](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)
- [Awesome Think with Images for LVLMs](https://github.com/zhaochen0110/Awesome_Think_With_Images) (A broader list covering more than just fine-grained visual understanding)
