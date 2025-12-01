# **Thesis Experiments Repository**

## **Comparative Evaluation of Prompt Engineering Techniques for NLP Tasks on YouTube AI Transcripts Using LLMs**

### **Overview**

This repository is part of my MSc. thesis titled:
**“A Comparative Evaluation of Prompt Engineering Techniques for Summarisation, Topic Classification, Question Generation, and Key Concept Extraction on YouTube AI Transcripts Using Large Language Models.”**

The research investigates how different prompt engineering strategies and large language models (LLMs) perform across four NLP tasks using long, noisy YouTube transcripts generated through Automatic Speech Recognition (ASR). The focus is on evaluating accuracy, consistency, robustness, and task-specific performance across a range of models and prompting approaches. The study contributes insights into the reliability and suitability of LLMs for educational content processing and long-document NLP scenarios.

### **Thesis Idea**

The thesis aims to systematically examine how varying prompting techniques influence the performance of multiple LLMs across four important NLP tasks:

1. Summarisation
2. Topic Classification
3. Question Generation
4. Key Concept Extraction

YouTube educational transcripts represent real-world learning materials that often contain imperfections due to ASR. By using these transcripts, the research evaluates how well LLMs handle natural, unstructured educational content. The study compares multiple prompting techniques and model families to determine the optimal strategies for generating high-quality outputs across different tasks.

### **Repository Structure**

The repository is organised to reflect all experimental outputs, evaluations, and code used throughout the thesis. Each experiment folder represents a specific model–prompting combination or batch.

**1. Generated Outputs (Excel)**

**Content:**
Each experiment contains excel files with the generated outputs for all four tasks, including summaries, predicted topics, question–answer pairs, and extracted key concepts.

**Purpose:**
These files provide clear examples of the model outputs and are used for qualitative analysis.

**2. Evaluation Metrics (JSON)**

**Content:**
Each experiment includes an Excel file containing all computed evaluation metrics, such as:

ROUGE-L F1, BLEU, and BERTScore for summarisation
Accuracy, F1-weighted, and F1-macro for topic classification
BLEU, Diversity, and Answerability for question generation
Precision@10, Recall@10, and F1@10 for key concept extraction

**Purpose:**
The Json files form the quantitative basis for comparing model and prompt performance across tasks.

**3. Final Thesis Code (Code Folder)**

**Content:**
All scripts used for dataset processing, chunking transcripts, prompt construction, LLM API integration, output generation, logging, and metric evaluation.

**Purpose:**
This section ensures reproducibility of the experiments and transparency of the methodology.

### **Experimental Context and Objectives**

The experiments in this repository address several research objectives:

**1. Comparative Prompting Analysis:** Assessment of Zero-Shot, Few-Shot, Instruction-Based, Chain-of-Thought, and Role-Based prompting.

**2. Cross-Model Evaluation**

Testing multiple LLMs, including:

Gemini models (2.5 Flash and Pro), LLaMA models (3.1 and 3.3 variants), GPT-OSS-20B and other open-source models, Kimi K2 models

Experiments were executed through Google Generative AI and Groq inference platforms.

**3. Long-Document Processing:** Evaluation of model performance on long ASR transcripts and the effectiveness of chunking strategies.

**4. Quantitative and Qualitative Assessment:** Computation of multiple evaluation metrics complemented by qualitative inspection of outputs.

**5. Reproducibility:** Ensuring that all experiments, output files, and scripts can be replicated using the provided code.

### **How to Use This Repository**

**1. Review Generated Outputs:** Open the PDF files to examine the summaries, topics, Q&A sets, and key concepts produced by each model–prompt combination.

**2. Explore the Metrics:** Use the Excel sheets to study the detailed performance metrics for each experiment.

**3. Run or Modify Code:** Open the code folder to examine or execute the scripts used for the experiments.
