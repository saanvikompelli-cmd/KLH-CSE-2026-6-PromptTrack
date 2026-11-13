
# PromptTrack – Prompt Versioning and Regression Testing using LLM-as-a-Judge

## 1. Project Title
**Prompt Versioning and Regression Testing using LLM-as-a-Judge**

**Short Project Name:** PromptTrack

## 2. Team Details

| Student ID | Name |
|---|---|
| 2520030128 | R.C. Sai Sharan |
| 2520030083 | Kompelli Saanvi |

**Team ID:** 6  
**Academic Year:** 2026–2027  
**Branch:** AIML  
**Department:** Computer Science and Engineering  
**University:** KLH University

## 3. Supervisor Details

**Supervisor Name:** Mr.Shaik Asif

## 4. Abstract

Large Language Models (LLMs) such as ChatGPT and Gemini are widely used for generating text, answering questions, and performing different tasks. The quality of their responses mainly depends on the prompts provided by users. Even small changes in prompts can affect the accuracy and quality of AI-generated responses.

This project proposes a system called PromptTrack for managing different versions of prompts and checking their performance. Whenever a prompt is modified, regression testing is performed using predefined test inputs to identify whether the new version improves or reduces response quality.

An LLM-as-a-Judge approach is used to evaluate generated responses based on accuracy, relevance, clarity, and instruction following. The system compares different prompt versions and identifies performance changes.

The main objective is to make prompt management, testing, and evaluation easier and more reliable.

## 5. Objectives

- To maintain and manage multiple versions of AI prompts.
- To perform automated regression testing on modified prompts.
- To evaluate AI-generated responses using LLM-as-a-Judge.
- To compare the performance of different prompt versions.
- To identify performance improvements and reductions.
- To improve the consistency and reliability of AI-generated responses.

## 6. Proposed Technologies

| Component | Technology |
|---|---|
| Programming Language | Python |
| AI Model API | Google Gemini API |
| Database | MongoDB Atlas |
| Frontend | Streamlit |
| Backend | Python |
| Version Control | Git and GitHub |
| Testing | Automated Test Cases |

## 7. Project Modules

1. **Prompt Management:** Create, save, and manage different prompt versions.
2. **Prompt Versioning:** Maintain the history of modified prompts.
3. **Regression Testing:** Test different prompt versions using predefined inputs.
4. **LLM-as-a-Judge:** Evaluate generated responses using predefined criteria.
5. **Performance Comparison:** Compare evaluation scores between prompt versions.
6. **Results Dashboard:** Display test results and performance comparisons.

## 8. Project Folder Structure

```text
PromptTrack/
│
├── src/
│   └── Source code files
│
├── docs/
│   └── Project documentation
│
├── data/
│   └── Test datasets and sample inputs
│
├── results/
│   └── Evaluation results and comparisons
│
├── reports/
│   └── Abstract, literature survey and research papers
│
└── README.md
```

## 9. Setup and Execution Instructions

### Prerequisites

- Python 3.10 or above
- Visual Studio Code
- Git
- Google Gemini API Key
- MongoDB Atlas Account
- Internet Connection

### Installation

1. Clone the repository:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

2. Open the project folder:

```bash
cd PromptTrack
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate the virtual environment on Windows:

```bash
venv\Scripts\activate
```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

6. Configure the Gemini API key and MongoDB connection string using environment variables.

7. Run the application using the appropriate project entry-point file.

**Note:** Execution instructions and dependencies will be updated as implementation progresses.

## 10. Current Project Phase

**Phase 1 – Research and Planning**

- Project title finalized.
- Abstract prepared.
- Research papers collected.
- Literature survey prepared.
- GitHub repository structure planned.
- Technology stack identified.
- Project feasibility and objectives analyzed.

**Next Phase:** System Design and Implementation.

## 11. Expected Outcome

The expected outcome is a working application that allows users to manage different prompt versions, perform regression testing, evaluate AI-generated responses, and compare performance results through a dashboard.

## 12. References

1. Wanqin Ma, Chenyang Yang, and Christian Kästner, "(Why) Is My Prompt Getting Worse? Rethinking Regression Testing for Evolving LLM APIs," CAIN 2024.
2. Anshul Bagaria et al., "Judging LLM-as-a-Judge: Concerning Rubric Artifacts in LLM-based Automated Text Generation Evaluation," 2026.

---

**Project Name:** PromptTrack  
**Team ID:** 6  
**Academic Year:** 2026–2027
