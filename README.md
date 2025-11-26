

### **I. The Frontier: Agents, Reasoning & Generation**

*The cutting edge of current AI development (2024–2025), focusing on self-learning agents, reasoning (System 2) capabilities, and flow-based generation.*

| Name | Relevance / Importance | Link |
| :--- | :--- | :--- |
| **Welcome to the Era of Experience** | **New Paradigm.** David Silver & Rich Sutton's manifesto arguing that AI is shifting from learning from human data (limited) to learning from agentic experience (unlimited). | [PDF (DeepMind/Alberta)](https://www.google.com/search?q=http://incompleteideas.net/IncIdeas/SilverSutton2025.pdf) |
| **Kimi K2: Open Agentic Intelligence** | **Agentic Architecture.** The technical report for Moonshot AI's Kimi K2, detailing a 1T parameter MoE model designed specifically for long-horizon agentic tasks and "slow thinking" reasoning. | [Arxiv](https://arxiv.org/abs/2507.20534) |
| **DeepSeekMath (GRPO Source)** | **RL for Reasoning.** This paper introduced **GRPO** (Group Relative Policy Optimization), the critical RL technique used in DeepSeek-R1/V3 to incentivize reasoning without a value function model. | [Arxiv](https://arxiv.org/abs/2402.03300) |
| **FLUX.1 Kontext** | **In-Context Generation.** The specific paper for Black Forest Labs' "Kontext" model, introducing Flow Matching for in-context editing and generation in latent space. | [GitHub/BibTeX](https://github.com/black-forest-labs/flux) |
| **Flow Matching for Generative Modeling** | **Flux Foundation.** Often called the "Flux paper," this establishes the theoretical basis (Flow Matching) that supersedes standard diffusion for models like FLUX.1 and Stable Diffusion 3. | [Arxiv](https://arxiv.org/abs/2210.02747) |

-----

### **II. Modern Architectures & Optimization**

*The building blocks of current LLMs and image models. Understanding these is crucial for model training and efficiency.*

| Name | Relevance / Importance | Link |
| :--- | :--- | :--- |
| **Scalable Diffusion Models with Transformers (DiT)** | **SORA/SD3 Architecture.** The "Diffusion Transformer" paper. It replaced the U-Net with a Transformer backbone, enabling the scaling of image/video generation (used in Sora, Flux, SD3). | [Arxiv](https://arxiv.org/abs/2212.09748) |
| **Direct Preference Optimization (DPO)** | **Alignment.** Revolutionized RLHF by removing the need for a separate reward model, optimizing the policy directly on preference data. Stable & computationally efficient. | [Arxiv](https://arxiv.org/abs/2305.18290) |
| **Mamba 1: Linear-Time Sequence Modeling** | **SSM Architecture.** Introduced Selective State Spaces, offering a viable alternative to Transformers with linear scaling (vs. quadratic) for long contexts. | [Arxiv](https://arxiv.org/abs/2312.00752) |
| **Mamba-2 / Transformers are SSMs** | **Architecture Bridging.** The follow-up paper unifying SSMs and Transformers via Structured State Space Duality (SSD), improving training efficiency on GPUs. | [Arxiv](https://arxiv.org/abs/2405.21060) |
| **GQA: Training Generalized Multi-Query Transformer** | **Inference Efficiency.** "Multi-Grouped Query Attention." The standard attention mechanism for Llama 2/3 and DeepSeek, balancing speed (MQA) and quality (MHA). | [Arxiv](https://arxiv.org/abs/2305.13245) |

-----

### **III. Foundational & Philosophy**

*The "Old Testament" of modern AI. Essential context for why the current methods work.*

| Name | Relevance / Importance | Link |
| :--- | :--- | :--- |
| **Attention Is All You Need** | **The Origin.** The original Transformer paper (Vaswani et al., 2017). The foundation of practically all modern Generative AI. | [Arxiv](https://arxiv.org/abs/1706.03762) |
| **The Bitter Lesson** | **Core Philosophy.** Rich Sutton's famous essay arguing that general methods that leverage computation (search and learning) always eventually beat human-engineered domain knowledge. | [Blog Post](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) |
| **Adam: A Method for Stochastic Optimization** | **The Optimizer.** The default optimization algorithm used to train virtually every modern neural network foundation model. | [Arxiv](https://arxiv.org/abs/1412.6980) |

-----

### **Recommended Next Step**

Would you like me to generate a **"1-Paragraph Summary"** for any specific paper in this list to help you decide which one to read first?
