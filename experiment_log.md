# Q4 – NotebookLM Experiment Log

## 1. Test T01 – Source-Grounded Question Answering

**Purpose:** Evaluate NotebookLM's ability to answer academic questions using uploaded documents and provide supporting citations.

### Test Prompt

> According to the uploaded AASB S2 document, what are the four core content areas of climate-related financial disclosures? Briefly explain each area in simple academic English. Provide citations to the relevant sections of the source document. Do not use information that is not supported by the uploaded sources.

### Observed Output

NotebookLM identified the following four disclosure areas:

1. Governance – Paragraphs 5–7
2. Strategy – Paragraphs 8–23
3. Risk Management – Paragraphs 24–26
4. Metrics and Targets – Paragraphs 27–37

The response included explanations and multiple clickable citation markers linked to the uploaded AASB S2 document.

### Evaluation

| Criterion | Observation | Assessment |
|---|---|---|
| Accuracy & Relevance | Correctly identified the four core disclosure areas and addressed the question directly. | Good |
| Completeness | Explained all four areas with supporting details and paragraph references. | Comprehensive |
| Citation Quality | Provided clickable citations, but specific supporting passages were not fully verified. | Partially verified |
| Academic Usefulness | Simplified reporting requirements into clear explanations for students. | Highly useful |
| Limitations | Detailed explanations require checking against the original standard. | Human verification required |

**Conclusion:** NotebookLM provided a useful and relevant academic explanation. However, although a citation opened the correct AASB S2 document, the precise supporting passage was not fully verified.

---

## 4. Test T02 – Multi-Source Comparison

**Purpose:** Evaluate NotebookLM's ability to compare multiple Australian sustainability reporting documents while preserving their different roles.

### Test Prompt

> Compare the roles of AASB S2 and ASIC Regulatory Guide 280 (RG 280) in Australia's sustainability reporting framework.
>
> Please:
> 1. Explain the main purpose of each document.
> 2. Compare their scope, reporting requirements, and regulatory roles in a concise table.
> 3. Explain how the two documents complement each other.
> 4. Include citations from both uploaded documents for the key findings.
> 5. Identify any important differences between mandatory reporting requirements and regulatory guidance.
>
> Use only the uploaded sources. If a point is not clearly supported by the documents, state this rather than making assumptions.

### Observed Output

NotebookLM generated a comparison covering:

- The main purpose of AASB S2 and ASIC RG 280.
- Issuing bodies and legal status.
- Reporting scope and applicability.
- Technical disclosure requirements and regulatory oversight.
- How reporting standards and regulatory guidance complement each other.

The answer included citations referring to the uploaded documents.

### Evaluation

| Criterion | Observation | Assessment |
|---|---|---|
| Accuracy & Relevance | Correctly distinguished AASB S2 reporting standards from ASIC RG 280 regulatory guidance. | Good |
| Completeness | Covered purpose, scope, legal status and regulatory responsibilities. | Comprehensive |
| Citation Quality | Provided citations from both documents, but specific claims were not fully verified. | Partially verified |
| Academic Usefulness | Simplified complex regulatory information through a structured comparison table. | Highly useful |
| Limitations | Some legal interpretations may be oversimplified or overly confident. | Human verification required |

**Conclusion:** NotebookLM helped explain the relationship between reporting standards and regulatory guidance. However, detailed legal and compliance claims should be checked against the original documents.

---

## 5. Test T03 – Study Guide Generation

**Purpose:** Evaluate NotebookLM's ability to transform multiple academic documents into useful revision materials.

### Test Prompt

> Using the three uploaded Australian sustainability reporting documents, create a concise study guide for university students.
>
> Include:
> 1. A brief overview of Australia's sustainability reporting framework.
> 2. Five key concepts explained in simple English.
> 3. The roles of AASB, ASIC, and Treasury.
> 4. Three exam questions with short answers.
>
> Keep it under 500 words, use only the uploaded sources, and include citations.

### Observed Output

NotebookLM generated a study guide containing:

**Framework Overview:** Australia's sustainability reporting framework and mandatory climate-related disclosures.

**Five Key Concepts:**
1. Scope 1, 2 and 3 emissions
2. Climate scenario analysis
3. Four core disclosure areas
4. Modified liability settings
5. Sustainable finance taxonomy

**Institutional Roles:** The different responsibilities of AASB, ASIC and the Australian Treasury.

**Practice Questions:** Three examination-style questions with short model answers covering reporting legislation, liability protections and institutional responsibilities.

### Evaluation

| Criterion | Observation | Assessment |
|---|---|---|
| Accuracy & Relevance | Summarised key concepts and broadly distinguished the roles of AASB, ASIC and Treasury. | Generally accurate |
| Completeness | Included all requested study guide sections and three practice questions. | Comprehensive |
| Citation Quality | Included citations, but supporting passages were not independently verified. | Partially verified |
| Academic Usefulness | Converted complex documents into structured revision notes and practice questions. | Highly useful |
| Limitations | Simplified legal requirements and technical reporting details. | Human review required |

**Conclusion:** NotebookLM produced useful revision materials, but some technical details and legal interpretations require verification against the original sources.

---

## 6. Consolidated Experimental Findings

| Criterion | Overall Finding |
|---|---|
| Accuracy & Relevance | All three tests generated generally relevant responses. |
| Completeness | The outputs addressed the main requested components. |
| Citation Quality | Citations were present, but individual supporting claims were not fully verified. |
| Academic Usefulness | Supported research, document comparison and exam preparation. |
| Limitations | Oversimplification, incomplete citation verification and potential over-reliance on AI-generated content. |

### Overall Assessment

The three experiments suggest that NotebookLM can be a useful supplementary academic research assistant. It helped organise information from complex Australian sustainability reporting documents and generated accessible learning materials.

However, the experiments were limited to three tests using three selected public documents. Citation availability does not guarantee factual accuracy, and no systematic reliability or fairness evaluation was conducted.

NotebookLM is therefore suitable for supporting academic research and revision, provided users verify important claims against the original sources.

## 7. Experiment Limitations

- Only three controlled tests were performed.
- The same three Australian documents were used across the tests.
- Citation verification was incomplete.
- No independent benchmark or quantitative accuracy assessment was conducted.
- Outputs may vary across NotebookLM sessions and future model updates.
- No confidential student or university records were used.

## 8. Evidence

Supporting screenshots should be stored in the `evidence/` folder:

- `Q4_01_Sources.png` – Three uploaded Australian documents.
- `Q4_02_T01_QA.png` – Source-based question answering.
- `Q4_03_T01_Citation.png` – Citation preview.
- `Q4_04_T02_Comparison.png` – Multi-source comparison.
- `Q4_05_T03_Study_Guide.png` – Generated study guide.
- `Q4_06_T03_Exam_Questions.png` – Practice questions and answers.

The screenshots document observed NotebookLM outputs. They do not independently establish that every generated claim is factually correct.
