# AI-Powered Plagiarism Detection & Grading System for CRP Theses

## 📌 Overview
This project presents an **AI-driven plagiarism detection and automated grading model** specifically designed for **Computing Research Project (CRP) theses**. Unlike traditional tools that only detect exact matches, this system identifies **AI-generated text**, **paraphrased plagiarism**, and evaluates **academic quality** — providing a holistic assessment solution for educators.

## 🎯 Key Features
- **Multi-Task Detection**: Identifies direct copy-paste, paraphrased content, and AI-generated text
- **Automated Grading**: Evaluates thesis against predefined assessment criteria
- **Semantic Analysis**: Uses **RoBERTa** fine-tuned for domain-specific language
- **User-Friendly Web Interface**: Generates visual reports with highlighted sections and risk scores
- **Integrated Workflow**: Combines detection, grading, and feedback in one platform

## 🧠 Model & Methodology
- **Base Model**: RoBERTa fine-tuned for academic text analysis
- **Detection Pipeline**:
  1. Preprocessing (anonymization, chunking, text extraction)
  2. Semantic similarity matching with assessment rubrics
  3. AI-generated text detection using transformer embeddings
  4. Grading logic based on plagiarism density, AI content %, and criteria fulfillment
- **Libraries**: Transformers, Sentence-Transformers, NLTK, Matplotlib/Plotly for visualization

## 📊 Results
- **Overall Accuracy**: 75% (with only 6 annotated CRP theses)
- **Outperforms traditional tools** in detecting paraphrased and AI-generated plagiarism
- **Integrated four tasks**: AI detection, plagiarism checking, criteria verification, automated grading
- **Academic feedback**: Lecturers found the system intuitive and efficient for real-world use

## 🚀 Future Work
- Extend to **multi-modal analysis** (source code, diagrams, datasets)
- Integrate with **Learning Management Systems** (Moodle, Blackboard)
- Expand training dataset with theses from multiple document types (Logbook, Proposal, Observation sheet)
- Develop **adaptive detection** to keep pace with evolving AI writing tools

## 🛠️ Installation & Usage
*(Instructions will be added once the codebase is uploaded.)*

## 📚 References
- *Beyond Black Box AI-Generated Plagiarism* (arXiv, 2023)
- *Testing of Detection Tools for AI-Generated Text* (arXiv, 2025)
- *Survey on Plagiarism Detection in Large Language Models* (arXiv, 2012)

## 👥 Contributors
- **MH. Rifthi Ahamed** – Developer & Researcher  
- **AL. Jubailah Begum** – Supervisor  
- **ALF. Sajeetha** – Assessor  

## 📄 License
This project is intended for academic and research purposes. Please contact the author for permissions regarding reuse or extension.
