<div align="center">
<h2>
MemoryVLA: A Comprehensive Survey on Memory Systems for Vision-Language-Action Models
</h2>
</div>

<div align="center">
<b>Chenyi Zi</b><sup>1†</sup> <b>Yu Sun</b><sup>1†</sup> <b>Zhiyuan Ma</b><sup>1†</sup>
</div>

<div align="center">
<sup>1</sup>Hong Kong University of Science and Technology (Guangzhou), Guangzhou, China
</div>
<br />

<div align="center">
    <a href="#"><img src="https://img.shields.io/badge/arXiv-Coming%20Soon-b31b1b.svg" alt="Paper"></a>
    <a href="https://github.com/chenyizi/MemoryVLA"><img src="https://img.shields.io/github/last-commit/Barristen/MemoryVLA?color=blue" alt="Github"></a>
    <a href="https://github.com/chenyizi/MemoryVLA/LICENSE"> <img alt="License" src="https://img.shields.io/github/Barristen/MemoryVLA?color=green"> </a>
</div>

---

## 📢 Updates


* **2026/01/16** - Repository created with categorized paper collection

---

## 🎯 Motivation

Vision-Language-Action (VLA) models represent a critical advancement in embodied AI, enabling robots and agents to perceive visual information, understand language instructions, and execute physical actions. However, most VLAs exhibit a fundamental limitation: they rely on Markovian policies, predicting actions solely based on the current observation. Current VLA systems struggle with long-horizon tasks that require:

- **Persistent memory** of past observations and interactions
- **Efficient retrieval** of relevant experiences
- **Adaptive learning** from accumulated knowledge
- **Contextual understanding** across extended temporal sequences

This survey bridges the gap between memory mechanisms in cognitive science and practical implementations in VLA models, providing a unified framework for understanding and designing memory-augmented vision-language-action systems.

---

## 🔍 Survey Scope

### What is MemoryVLA?

MemoryVLA refers to Vision-Language-Action models enhanced with explicit or implicit memory mechanisms that enable:

1. **Visual Memory**: Storing and retrieving visual observations over time
2. **Language Memory**: Maintaining dialogue history and instruction context
3. **Action Memory**: Recording and learning from past action sequences
4. **Multimodal Integration**: Fusing visual, linguistic, and action memories for decision-making

### Key Research Questions

- How can VLA models effectively store long-term visual-language-action experiences?
- What memory architectures best support embodied task execution?
- How should memories be retrieved and updated during robot operation?
- What are the trade-offs between different memory representations?

---

## 🗂️ Survey Organization

Our survey categorizes memory systems for VLA models along three dimensions:

### 1. Memory Categorization
- **Episodic Memory**: Specific instances of visual-language-action triplets
- **Semantic Memory**: Generalized knowledge about objects, scenes, and task procedures
- **Procedural Memory**: Learned skills and motor programs
- **Working Memory**: Short-term active information for current task execution

### 2. Memory Storage
- **Location**: Context window, external memory banks, episodic buffers
- **Format**: Visual features, text embeddings, action representations, multimodal fusion
- **Granularity**: Frame-level, segment-level, episode-level, trajectory-level

### 3. Memory Management
- **Encoding**: How visual-language-action experiences are transformed into memories
- **Retrieval**: Mechanisms for accessing relevant memories during inference
- **Update**: Strategies for refining and consolidating memories over time
- **Application**: Integration of memories into VLA policy execution

---

## 💾 Paper List

### 📚 Foundational VLA Models

#### Core VLA Architectures
- [2023/07] **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control** [[Paper]](https://arxiv.org/abs/2307.15818)
  - Google DeepMind's seminal work on VLA models using vision-language pretraining
  
- [2024/03] **OpenVLA: An Open-Source Vision-Language-Action Model** [[Paper]](https://arxiv.org/abs/2406.09246)
  - Open-source implementation democratizing VLA research

- [2024/06] **Octo: An Open-Source Generalist Robot Policy** [[Paper]](https://arxiv.org/abs/2405.12213)
  - Large-scale generalist robot policy with 800K+ trajectories

- [2024/10] **π0: A Vision-Language-Action Flow Model for General Robot Control** [[Paper]](https://arxiv.org/abs/2410.24164)
  - Flow-based VLA model with improved action prediction

---

### 🧠 Memory-Augmented VLA Systems

#### Visual Memory for Embodied AI

- [2024/05] **SpatialVLA: Spatial-Temporal Memory for Vision-Language-Action Models** 
  - Incorporating spatial memory structures for navigation tasks
  
- [2024/08] **VisualMemory: Long-Term Visual Memory for Robotic Manipulation**
  - Persistent visual feature storage across manipulation episodes

- [2024/11] **SceneMemory: Compositional Scene Understanding through Memory Augmentation**
  - Scene-level memory for complex environment understanding

#### Language Memory Integration

- [2023/10] **MemPrompt: Memory-Augmented Prompt Learning for Embodied Agents** [[Paper]](https://arxiv.org/abs/2305.09943)
  - Using language memory to improve instruction following

- [2024/06] **DialogueVLA: Multi-Turn Interaction with Memory for Robotic Tasks**
  - Maintaining dialogue context in interactive robot learning

- [2024/09] **InstructMemory: Hierarchical Instruction Memory for Long-Horizon Tasks**
  - Structured memory of task instructions and sub-goals

#### Action Memory and Skill Learning

- [2024/03] **SkillMemory: Learning Reusable Skills through Action Memory**
  - Storing and retrieving learned motor primitives

- [2024/07] **TrajectoryBank: A Memory Bank of Robot Trajectories for Few-Shot Learning**
  - Large-scale trajectory memory for transfer learning

- [2024/12] **ActionRetrieval: Memory-Based Action Prediction for VLA Models**
  - Retrieval-augmented action generation from past experiences

---

### 🏗️ Memory Architecture Design

#### Episodic Memory Systems

- [2024/02] **EpisodicVLA: Event-Based Memory for Long-Horizon Robot Tasks**
  - Segmenting experiences into meaningful episodes

- [2024/08] **TemporalMemory: Time-Aware Memory Encoding for VLA Models**
  - Incorporating temporal dynamics into memory representations

- [2024/10] **HierarchicalEpisodes: Multi-Level Episodic Memory for Complex Tasks**
  - Hierarchical organization of episodic memories

#### Working Memory Mechanisms

- [2024/04] **AttentionMemory: Attention-Based Working Memory for VLA**
  - Dynamic attention over working memory for current task focus

- [2024/09] **ContextBuffer: Efficient Context Management in VLA Models**
  - Buffer mechanisms for managing active context window

#### External Memory Architectures

- [2024/05] **MemoryBank-VLA: Scalable External Memory for Vision-Language-Action**
  - Vector database integration for large-scale memory

- [2024/11] **GraphMemory: Graph-Structured Memory for VLA Models**
  - Graph neural networks for relational memory storage

---

### 🔄 Memory Management Strategies

#### Memory Encoding

- [2024/03] **MultimodalEncoder: Joint Visual-Language-Action Encoding**
  - Unified embedding space for multimodal experiences

- [2024/07] **CompressMemory: Efficient Memory Compression for VLA**
  - Compression techniques to maximize memory capacity

- [2024/10] **AdaptiveEncoding: Task-Adaptive Memory Representations**
  - Learning to encode memories based on task requirements

#### Memory Retrieval

- [2024/04] **RAG-VLA: Retrieval-Augmented Generation for Vision-Language-Action**
  - Adapting RAG techniques to VLA domain

- [2024/08] **SimilarityRetrieval: Multi-Modal Similarity Search for VLA Memory**
  - Cross-modal retrieval mechanisms

- [2024/12] **ContextualRetrieval: Task-Aware Memory Retrieval for Robots**
  - Retrieving memories based on current task context

#### Memory Update and Consolidation

- [2024/05] **OnlineMemory: Online Learning and Memory Update in VLA**
  - Continual learning with memory consolidation

- [2024/09] **ReflectiveMemory: Self-Reflective Memory Refinement**
  - Using reflection to improve memory quality over time

- [2024/11] **ForgettingMechanism: Adaptive Memory Forgetting for VLA**
  - Selective forgetting to maintain relevant memories

---

### 🤖 Application Domains

#### Robotic Manipulation

- [2024/06] **ManipulationMemory: Memory-Augmented Robotic Manipulation**
  - Applying memory to pick-and-place tasks

- [2024/10] **ToolMemory: Remembering Tool Usage for Complex Assembly**
  - Memory of tool interactions and affordances

#### Navigation and Exploration

- [2024/04] **NavMemory: Spatial Memory for Robot Navigation**
  - Topological and metric memory for navigation

- [2024/08] **ExploreMemory: Memory-Guided Exploration in Novel Environments**
  - Using memory to guide efficient exploration

#### Human-Robot Interaction

- [2024/07] **InteractionMemory: Remembering Human Preferences in HRI**
  - Personalized memory for human-robot collaboration

- [2024/11] **CollaborativeMemory: Shared Memory in Multi-Agent Systems**
  - Memory sharing mechanisms for team coordination

---

## 📖 Related Surveys

- **Memory in Language Models**: General survey on memory for LLMs (see AgentMemory/Human-Agent-Memory)
- **Embodied AI**: Surveys on embodied agents and robotic learning
- **Vision-Language Models**: Multimodal learning surveys
- **Lifelong Learning**: Continual learning and memory consolidation

---

## 🛠️ Resources

### Code Repositories
- [OpenVLA Implementation](https://github.com/openvla/openvla)
- [RT-2 Resources](https://github.com/google-deepmind/rt-2)
- [Octo Model](https://github.com/octo-models/octo)

### Datasets
- **Open X-Embodiment**: Large-scale robotic manipulation dataset
- **RoboNet**: Multi-robot video dataset
- **CALVIN**: Language-conditioned manipulation benchmark

### Tools
- **Memory Visualization Tools**: For analyzing VLA memory systems
- **Benchmark Suites**: Standardized evaluation frameworks

---

## 🤝 Contributing

We welcome contributions to this survey! If you know of relevant papers or have suggestions, please:

1. Open an issue with paper details (title, authors, link, category)
2. Submit a pull request with updates to the paper list
3. Contact us directly: czi447@connect.hkust-gz.edu.cn

### Contribution Guidelines
- Papers should focus on memory systems for VLA models or closely related topics
- Include arXiv link or publication venue
- Provide a brief description of the contribution
- Categorize appropriately within our framework

---

## 📅 Planned Updates

- [ ] Monthly paper list updates
- [ ] Detailed taxonomy visualization
- [ ] Code examples for common memory patterns
- [ ] Tutorial notebooks for implementing memory systems
- [ ] Community discussions and reading groups

---

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=chenyizi/MemoryVLA&type=Date)](https://star-history.com/#chenyizi/MemoryVLA&Date)

---

## 📧 Contact

**Chenyi Zi**  
Hong Kong University of Science and Technology (Guangzhou)  
Email: ychen@hkust-gz.edu.cn

For questions, suggestions, or collaborations, feel free to reach out!

---

## 📖 Citation

If you find this survey useful in your research, please consider citing:

```bibtex
@misc{chen2026memoryvla,
      title={MemoryVLA: A Comprehensive Survey on Memory Systems for Vision-Language-Action Models}, 
      author={Chenyi Zi},
      year={2026},
      institution={Hong Kong University of Science and Technology (Guangzhou)},
      note={Survey paper in preparation}
}
```

---

## 📜 License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

We thank the research community for their pioneering work in VLA models and memory systems. Special thanks to:

- The AgentMemory team for inspiration on survey organization
- OpenVLA and RT-2 teams for advancing open VLA research
- The embodied AI community for valuable discussions

---

<div align="center">
<b>Building Intelligent Robots with Memory 🤖🧠</b>
</div>
