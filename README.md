# Could-an-LLM-qualify-for-the-MIT-Integration-Bee-An-AI-Learning-Experiment_Repo
# MIT Integration Bee LLM Experiment: Repository Overview
Welcome to the GitHub repository associated with the paper:  
> **“Could an LLM Qualify for the MIT Integration Bee?”**  
by Max Gregg, Michigan State University

This repository contains:

1. **Data Files (CSVs)**
2. **Jupyter Notebooks**
3. **Figures, Plots, & Images**
4. **LaTeX Files & Integration Bee Materials**
5. **Textbooks / Reference PDFs**
6. **Drafts & Supporting Documents**
7. **Miscellaneous**

Below is a breakdown of the directory structure and file groups.

---

## 1. Data Files (CSVs)

These files capture the AI-generated responses, assessments, and experimental results. Each CSV typically includes integrals, model responses, correctness labels, and grader outputs.

- **`df_35_resp_aug5.csv`, `df_4o_aug5.csv`, `df_opus_20240807-1751.csv`**, etc.  
  - *Contain response data from different models (GPT 3.5, GPT-4 “Opus,” “Sonnet,” etc.) with timestamps indicating the date or version.*  
- **`df_assistant_4o_mini_fullbook_20240808-0010.csv`**  
  - *Results from the “mini” assistant model with a full textbook.*  
- **`df_assistant_4o_optimizedbook_20240808-2354.csv`**  
  - *Results from the GPT-4 assistant with a token-optimized textbook.*  
- **`test.csv`, `random_25_samples.csv`, `models_prg.csv`, `models_pre.csv`**  
  - *Smaller or test CSV files used in debugging or partial subsets.*  

---

## 2. Jupyter Notebooks

These IPython notebooks document the experimental workflow, prompt engineering, and analysis.

- **`Responses_3.5_Turbo.ipynb`, `Responses_4o_Aug5.ipynb`, `Responses_Assistant_4o_OptimizedBook_Aug8.ipynb`, `Responses_Opus_Aug7.ipynb`, etc.**  
  - *Scripts to query each model for its solution to various integrals and record results in CSV form.*  
- **`Responses_IDA.ipynb`**  
  - *Introductory Data Analysis (IDA) notebook: basic inspections, summarizing correctness rates, spot checks, etc.*  
- **`LaTeXfile.ipynb`, `GPTIntegralChat.ipynb`**  
  - *Utility or exploratory notebooks for generating LaTeX strings, exploring chat-based integrals, etc.*  
- **`Responses_4High_Aug6.ipynb`, `Responses_4oLow_Aug5.ipynb`**  
  - *High/Low temperature runs for GPT-4 models.*  

---

## 3. Figures, Plots, & Images

Visualization of results, confusion matrices, and other graphics used in the paper.

- **`correctness_table_1.png`, `confmatrx_ida_mitintegrals.png`, `confusion_matrices.pdf`**  
  - *Overall results tables, integrated data analysis figures.*  
- **`confusion_matrix_*.png`** (e.g., GPT-4o, GPT-3.5 Turbo, Claude Opus)  
  - *Individual confusion matrices for each model.*  
- **`Timeline.jpg`**  
  - *Potential timeline or project flow illustration.*  

---

## 4. LaTeX Files & Integration Bee Materials

Files that contain or generate the integrals used from MIT Integration Bee qualifier tests. Some are test PDFs; others are the official LaTeX sources or partial solutions.

- **`mit_solns_LaTeX.py`, `LaTeX File for API.sty`, `qualifying_round_2024_refined.tex`, `qualifying_round_2024.tex`**  
  - *Python script(s) and `.tex` sources for generating integrals and solution sets.*  
- **`qualifying_round_20XX_test.pdf` and `qualifying_round_20XX_answers.pdf`**  
  - *Original or curated PDFs of MIT Integration Bee tests and solutions for various years (2010–2024).*  
- **`Integration_Bee_Questions_and_Answers.pdf`**  
  - *Likely a master reference containing Bee questions and official answers.*  

---

## 5. Textbooks / Reference PDFs

- **`optimized_calculus_textbook_comprehensive_v2.pdf`**  
  - *A compressed or token-optimized version of Gilbert Strang’s *Calculus* used for certain GPT-4 “assistant” runs.*  
- **`mitres_18_001_f17_full_book.pdf`**  
  - *Possibly a reference or original textbook used in the experiment.*  

---

## 6. Drafts & Supporting Documents

Word documents, PPT slides, and other materials related to paper drafting, proposals, or presentations.

- **`.docx` files** (e.g., `CMSE 890_DraftOne.docx`, `Qeios_Draft1_MG_MSU.docx`)  
  - *Drafts of the paper, proposals, or supplementary text.*  
- **`Training Chatbots to compete for the MIT Integration.pptx`**  
  - *Presentation slides summarizing the project.*  
- **`Max Gregg.pdf`**  
  - *Possibly a consolidated PDF or personal summary of the research.*  

---

## 7. Miscellaneous

- **`.ipynb_checkpoints`**  
  - *Auto-generated folder by Jupyter Notebook for checkpointing.*  
- **`formal-grammar-420315-6c5a14089d9a.json`**  
  - *JSON configuration file, possibly used for metadata or environment settings.*  
- **`2024_finals.pdf`, `2023_semifinal.pdf`, etc.**  
  - *Other Bee-related materials or bracket PDFs.*  
- **`Response to Presentations.docx`, `CMSE 890_Proposal.docx`, etc.**  
  - *Various supporting documents tied to academic milestones (proposals, responses, feedback).*

---

## How to Use This Repository

1. **Reproduce Experiments**  
   - Check out the Jupyter notebooks (`Responses_*.ipynb`) to see how integral queries were sent to different LLMs.  
   - **Data** needed for these experiments are in the CSVs prefixed with `df_`.  
2. **Explore Integration Bee Materials**  
   - Look in the **LaTeX files** and **PDF tests** folders for year-by-year Bee questions/solutions.  
3. **Reference Figures**  
   - Visual results (plots, confusion matrices) are available as images or PDFs in the “Figures” folder.  
4. **Optimized Textbook**  
   - The file `optimized_calculus_textbook_comprehensive_v2.pdf` is the compressed resource used to reduce token cost for GPT-4’s reference.

---

## License & Attribution

- **MIT Integration Bee Materials**  
  These are derived from official or publicly available competition documents. Please check MIT’s guidelines for any usage restrictions.  
- **Gilbert Strang’s “Calculus”**  
  The optimized version here is based on the OpenStax-licensed text. Attribution to the author and OpenStax is required if redistributing.  
- **Code & Data**  
  Unless otherwise specified, this repository is made available under an MIT License (or the license you choose). Refer to the `LICENSE.md` if provided.

If you make use of any portion of this repository in your research or teaching, please cite or link back to this GitHub repo and credit the original authors/publishers.

---

**Thanks for checking out this project!** If you have any questions or suggestions, feel free to open an issue or submit a pull request. This README was generated by ChatGPT o1 on January 24, 2025. 
