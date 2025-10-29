# 1. Simulation Methods

---

## 1.1  LLM-Based Simulation

| **Paper / Dataset / Framework** | **Summary / Domain** |
|----------------------------------|-----------------------|
| [**DIALOGIC: Controllable Dialogue Simulation with In-Context Learning**](https://aclanthology.org/2022.findings-emnlp.318.pdf) | Early controllable dialogue simulation using GPT-3 with turn-level annotations. |
| [**Simulating User Diversity in Task-Oriented Dialogue Systems using Large Language Models**](https://arxiv.org/abs/2502.12813) | Persona-based user diversity simulation leveraging LLMs to vary demographics, knowledge, and style. |
| [**Synthetic Patient-Physician Dialogue Generation from Clinical Notes Using LLM**](https://arxiv.org/abs/2408.06285) | Generates synthetic patient–doctor dialogues grounded in clinical notes; evaluated by clinicians. |
| [**Persona-Assigned Large Language Models Exhibit Human-Like Motivated Reasoning**](https://arxiv.org/abs/2506.20020) | Explores how persona conditioning induces human-like reasoning bias; relevant for believable patient personas. |
| [**SEADialogues: A Multilingual Culturally Grounded Multi-Turn Dialogue Dataset**](https://openreview.net/forum?id=b0eqQBoemi) | Large synthetic dataset across SE-Asian languages; useful for cross-cultural comprehension-gap studies. |
| [**MUSE: A Multimodal Conversational Recommendation Dataset with Scenario-Grounded User Profiles**](https://aclanthology.org/2025.findings-acl.58/) | Combines text and visual context with user profiles; demonstrates scenario-grounded dialogue generation. |
| [**DFLOW: Diverse Dialogue Flow Simulation with Large Language Models**](https://aclanthology.org/2025.realm-1.2/) | Uses decision-tree planning to produce diverse multi-turn flows; increases scenario coverage. |
| [**OmniChat: Enhancing Spoken Dialogue Systems with Scalable Synthetic Data for Diverse Scenarios**](https://arxiv.org/abs/2501.01384) | Scalable spoken-dialogue synthesis; blends text + speech for training multimodal chatbots. |
| [**Synthetic Online Conversations (SOC)**](https://huggingface.co/blog/marcodsn/soc-2508) | Hugging Face synthetic social-chat dataset; rich personas and “messy” realism. |
| [**Generative Agent Simulations of 1,000 People**](https://arxiv.org/pdf/2411.10109v1) | LLM-based generative agents emulating real survey participants; reproduces human trait distributions. |
| [**Synthetic Empathy**](https://aclanthology.org/2025.clpsych-1.13/) | Generates psychotherapy dialogues to train empathy-detection models; shows synthetic data can rival real. |
| [**CounseLLMe**](https://www.sciencedirect.com/science/article/pii/S2667118225000017) | Dataset of multilingual simulated mental-health counselling sessions comparing LLMs and human therapists. |

---

## 1.2  Multi-Agent and Reinforcement-Learning Frameworks

| **Framework / Paper** | **Focus / Contribution** |
|-------------------------|---------------------------|
| [**ASTRO: Automatic Strategy Optimization for Non-Cooperative Dialogues**](https://aclanthology.org/2025.findings-acl.22/) | Multi-agent self-play RL that evolves dialogue strategies autonomously. |
| [**Ask Patients with Patience (APP)**](https://arxiv.org/abs/2502.07143) | Medical dialogue framework using Bayesian active learning for patient-centered reasoning. |
| [**Persona-Aware LLM-Enhanced Multi-Session Dialogue (PALACE)**](https://aclanthology.org/2025.findings-acl.5/) | Maintains long-term persona consistency across sessions; useful for progressive patient modeling. |
| [**Co-Constructive Behavior of LLMs in Explanation Dialogues**](https://aclanthology.org/2025.sigdial-1.1/) | Studies how LLMs collaboratively refine explanations; informs adaptive clarification design. |
| [**Speculative End-Turn Detector for Efficient Speech Chatbot Assistant**](https://arxiv.org/abs/2503.23439) | Real-time end-turn detection; key for identifying hesitation or confusion pauses. |
| [**Trustworthy AI Psychotherapy: Multi-Agent LLM Workflow**](https://arxiv.org/html/2508.11398v2) | Multi-agent architecture for counselling and explainable reasoning under safety constraints. |
| [**LLMs Grading Clinical Reasoning in Virtual Patient Dialogues**](https://aclanthology.org/2025.sigdial-1.56/) | Uses LLMs as evaluators (“LLM-as-Judge”) for assessing medical students’ reasoning quality. |

---

### 🧩  Notes

- **Why include these:** together they represent the 2022–2025 shift toward *LLM-driven controllable and multi-agent user simulation*.  
- **Relevance to Task 1.A:** they establish the modeling foundations for our patient simulator—combining persona conditioning, controllable confusion generation, and RL-based adaptive dialogue.
