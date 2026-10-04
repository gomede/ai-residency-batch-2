# Artificial Intelligence Residency II

An advanced, project-based program covering deep learning, large language models, retrieval-augmented generation, and agent systems.

The program combines theoretical foundations, controlled experimentation, and software engineering to help participants build, evaluate, and operate AI systems.

## Program Overview

- **Duration:** 12 months
- **Teaching schedule:** 44 instructional weeks
- **Class hours:** 88 hours
- **Sessions:** Two-hour classes on Saturdays
- **Structure:** 12 modules with cumulative projects
- **Independent work:** Additional readings, experiments, and project development outside class hours

Class time may be redistributed across modules while preserving the total teaching hours.

## Target Audience

Graduates of the first AI residency or participants with equivalent knowledge and practical experience.

## Prerequisites

Participants should be familiar with:

- Python programming and data manipulation
- Introductory linear algebra, calculus, and probability
- Neural networks, backpropagation, activation functions, and loss functions
- Convolutional neural networks
- Feature engineering and dimensionality reduction
- Hyperparameter tuning and model evaluation
- Data pipelines and software engineering fundamentals

Experience with a deep learning framework is recommended. An initial diagnostic activity will identify gaps for guided study.

## Learning Objectives

By the end of the program, participants should be able to:

- Diagnose training problems and conduct reproducible experiments.
- Prevent data leakage and design appropriate evaluation protocols.
- Compare transfer learning and representation learning strategies.
- Explain and implement attention mechanisms and Transformer components.
- Understand tokenization, language modeling, and text generation.
- Adapt pretrained models and compare prompting with fine-tuning.
- Build RAG systems and evaluate retrieval and generation separately.
- Develop agents with controlled tools, explicit execution limits, and traceable actions.
- Integrate text and visual information.
- Deploy systems with versioning, monitoring, regression tests, and failure recovery.
- Communicate technical decisions through code, documentation, and experimental reports.

## Curriculum

| Month | Module | Practical Deliverable |
| --- | --- | --- |
| 1 | Advanced Training and Reliable Experimentation | Reevaluate an earlier project using baselines, controlled experiments, and a reproducible protocol. |
| 2 | Transfer Learning and Representation Learning | Compare training from scratch, frozen feature extraction, and fine-tuning under different amounts of labeled data. |
| 3 | Sequential Models and Attention | Compare recurrent and attention-based models on a sequential task, including error analysis. |
| 4 | Inside Transformers | Implement a small Transformer in PyTorch and verify dimensions, masks, gradients, and training behavior. |
| 5 | LLM Foundations and Text Generation | Train a small educational language model and build an evaluation set for pretrained models. |
| 6 | LLM Adaptation and Post-Training | Compare an original model, prompting, and fine-tuning on held-out data, including resource usage. |
| 7 | Information Retrieval and RAG | Build a document assistant with verifiable sources and separate retrieval and generation evaluations. |
| 8 | LLM Evaluation, Reliability, and Security | Build an evaluation suite covering answerable, unanswerable, ambiguous, and adversarial questions. |
| 9 | Agents, Tools, and Execution | Build an agent with controlled tools, action traces, and failure handling. |
| 10 | Orchestration and Multi-Agent Systems | Compare a fixed workflow, a single agent, and a multi-agent system on the same task. |
| 11 | Multimodal AI | Extend the assistant to documents containing images and tables, evaluating perception, retrieval, and generation separately. |
| 12 | Deployment, Operations, and Final Project | Deliver an integrated, reproducible, monitored system with documentation and a final demonstration. |

## Module Topics

### Month 1 — Advanced Training and Reliable Experimentation

Gradient diagnostics, residual connections, normalization, regularization, AdamW, learning rate schedules, mixed precision, random seeds, ablation studies, confidence intervals, group-based and temporal splits, and data leakage prevention.

### Month 2 — Transfer Learning and Representation Learning

Pretraining, feature extraction, layer freezing and unfreezing, fine-tuning, embeddings, contrastive learning, self-supervised learning, domain shift, and label efficiency.

### Month 3 — Sequential Models and Attention

RNNs, LSTMs, GRUs, encoder–decoder architectures, teacher forcing, attention, masking, variable-length sequences, temporal validation, and task-appropriate baselines.

### Month 4 — Inside Transformers

Self-attention, multi-head attention, positional representations, causal masks, residual connections, normalization, encoder and decoder architectures, and sequence-length complexity.

### Month 5 — LLM Foundations and Text Generation

BPE and Unigram tokenization, corpus preparation and deduplication, next-token prediction, cross-entropy, perplexity, temperature, top-k, top-p, context windows, in-context examples, and structured output validation.

### Month 6 — LLM Adaptation and Post-Training

Instruction data curation, supervised fine-tuning, parameter-efficient adaptation, LoRA, QLoRA, preference alignment, DPO, conceptual foundations of RLHF, distillation, catastrophic forgetting, and train–test contamination.

### Month 7 — Information Retrieval and RAG

Text embeddings, lexical and dense search, indexing, document chunking, metadata, hybrid retrieval, reranking, context selection, citations, abstention, Recall@k, and ranking metrics.

### Month 8 — LLM Evaluation, Reliability, and Security

Domain benchmarks, factuality, evidence support, human evaluation, rubrics, limitations of LLM-as-a-judge, regression tests, prompt injection, privacy, access control, cost, and latency.

### Month 9 — Agents, Tools, and Execution

Workflows versus agents, tool selection and invocation, input and output contracts, state, memory, planning, execution limits, timeouts, retries, idempotency, permissions, human approval, and execution logs.

### Month 10 — Orchestration and Multi-Agent Systems

Routing, task decomposition, parallel execution, handoffs, coordination, shared memory, context engineering, failure recovery, token budgets, termination criteria, and trajectory evaluation.

### Month 11 — Multimodal AI

Vision Transformers, image–text alignment, multimodal contrastive learning, vision–language models, document and chart understanding, multimodal retrieval, and perception errors.

### Month 12 — Deployment and Operations

Model serving, quantization, batching, caching, APIs, containers, CI/CD, versioning of models and data, prompt and index versioning, observability, load testing, quality monitoring, and rollback.

## Learning Approach

Each module follows four stages:

1. Foundations and guided reading
2. Guided implementation
3. Experimentation and failure analysis
4. Presentation and assessment

Activities include technical discussions, paper reading, hands-on laboratories, code reviews, and cumulative projects.

Training from scratch is limited to small educational models. Other activities use pretrained models compatible with the available infrastructure. Full RLHF and large-scale distributed training are conceptual or optional topics.

## Integrated Projects

### Months 1–3: Experimental Study of Models and Representations

Deliver reproducible code, baselines, ablation studies, variability analysis, and error analysis.

### Months 4–6: Language Modeling and Adaptation

Deliver an educational Transformer, an adapted language model, and independent evaluations before and after adaptation.

### Months 7–9: Document Assistant with Tools

Deliver source-based retrieval, response evaluation, and controlled tool execution.

### Months 10–12: Multimodal Agent System in Operation

Extend the assistant with multimodal capabilities, architecture comparisons, monitoring, and failure recovery.

## Final Project

The final project begins in Month 7.

Before the main experiments, participants must define:

- The problem and project scope
- The evaluation protocol and held-out test set
- The computational budget
- The relevant baselines and success metrics

Architecture choices must be supported by comparisons between applicable approaches, such as specialized models, prompting, RAG, fine-tuning, fixed workflows, and agents.

Final deliverables include:

- An integrated system
- Reproducible code and experiments
- Technical documentation
- An experimental report
- A final demonstration

## Assessment

| Criterion | Weight |
| --- | ---: |
| Experimental rigor and protocol suitability | 30% |
| Implementation correctness and quality | 25% |
| Results evaluation and error analysis | 20% |
| Engineering, documentation, and reproducibility | 15% |
| Technical communication and justification of decisions | 10% |
| **Total** | **100%** |

Assessment includes laboratories, reports, code reviews, presentations, and the final project defense.

System evaluation considers task quality, performance across subsets, evidence support, tool execution success, cost per completed task, and p95 latency, as appropriate to the application.

## Required Resources

- Python and PyTorch
- Version control
- Notebooks
- Libraries for pretrained models, adaptation, and retrieval
- A container environment
- CPU infrastructure and planned GPU access
- API access when included in the project budget

Dataset sources, licenses, and usage conditions must be documented. Dependency versions must be recorded for each project.

## References

### Core References

- Goodfellow, I., Bengio, Y., and Courville, A. — [Deep Learning](https://www.deeplearningbook.org/)
- Vaswani, A., et al. — [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- Hugging Face — [LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

### Additional References

- Hugging Face — [PEFT Documentation](https://huggingface.co/docs/peft/index)
- Hugging Face — [TRL Documentation](https://huggingface.co/docs/trl/index)
- Sentence Transformers — [Retrieve & Re-Rank](https://sbert.net/examples/sentence_transformer/applications/retrieve_rerank/README.html)
- Anthropic — [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)
- Anthropic — [Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)

## Program Flexibility

This curriculum is a proposed teaching guide. Content, sequence, activities, and class-hour distribution may be adjusted to the participants’ needs, available infrastructure, academic calendar, and institutional requirements while preserving the overall learning objectives and total teaching hours.

## Classes

### Introduction

https://drive.google.com/file/d/15HdwA7EyBv-9_fnCMS1etVZTx1_T4l_W/view?usp=sharing