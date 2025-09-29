# Benchmarking Expert Chatbot Personas

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Status](https://img.shields.io/badge/status-active-success.svg)

## Overview

This repository contains **Mini-Project 1** for *IPHS 391: Frontiers of AI* at Kenyon College. The project explores how **prompt engineering and persona design** influence the performance, tone, and usefulness of conversational AI systems.  
Created by **Murathan Kocaman**, a junior Economics major, the project focuses on designing, deploying, and benchmarking a specialized chatbot persona and evaluating its performance against a detailed rubric.

The central experiment builds a chatbot persona inspired by **Ali Ağaoğlu**, a well-known Turkish developer and entrepreneur recognized for his bold decision-making, street-smart instincts, and direct mentorship style. This influence shaped how the chatbot speaks, advises, and interacts — prioritizing instinct over abstraction and emphasizing practical wisdom over technical jargon.

---

## Methodology

1. **Persona Prompt Engineering**  
   - Designed the chatbot persona to reflect the communication style and worldview of Ali Ağaoğlu, including blunt advice, culturally grounded expressions, and a results-first mindset.  
   - Captured key personality traits such as confidence, directness, and experience-based storytelling.  
   - Used few-shot and in-context examples to ensure conversational consistency and natural tone.

2. **Evaluation Framework**  
   - Built a **quantitative rubric** (0–100) with weighted criteria to measure persona fidelity.  
   - Metrics included:
     - Persona Consistency
     - Conversational Format Fidelity
     - Expertise and Accuracy
     - Engagement and Voice
     - Adaptability to User Needs

3. **Benchmarking Conversations**  
   - Conducted controlled 10-turn conversations to test how well the chatbot embodied the Ağaoğlu-inspired persona.  
   - Evaluated the degree to which responses mirrored real-world mentorship dynamics, including instinctive decision-making and cultural framing.

---

## Results

- The chatbot achieved a **final persona fidelity score of 93/100**.
- Strong performance in maintaining tone, conversational style, and expert heuristics.
- Weaknesses were observed in verbosity and occasional deviation from target diction.
- The Ağaoğlu-style emphasis on narrative, directness, and decision-making instincts significantly improved engagement and user satisfaction.

---

## Files Description

| File | Description |
|------|-------------|
| `prompt_persona.txt` | The full system prompt defining the chatbot’s persona. |
| `metaprompt_history.txt` | Iterations and refinements of the prompt design process. |
| `chat_history.md` | Transcript of evaluation conversations. |
| `chat_rubric.txt` | Detailed evaluation rubric with scoring breakdown. |
| `chat_rubric_history.md` | Evolution of the rubric over time. |
| `mp1_chatbot_report.docx` | Final project report with analysis and conclusions. |

---

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/murathan9165/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas.git
   ```
2. Explore key files like `prompt_persona.txt` and `chat_rubric.txt` to understand the methodology.
3. Review `chat_history.md` to see the chatbot’s real-world interactions.

---

## Installation

No dependencies are required. The repository is self-contained and suitable for review as an academic and research artifact.

---

## Contributing

Contributions are welcome for:
- Expanding persona benchmarks  
- Improving evaluation rubrics  
- Adding more conversation transcripts

Please fork the repo and submit a pull request.

---

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

---

## Citation

If referencing this project for academic work, cite as:

```
Kocaman, Murathan. "Benchmarking Expert Chatbot Personas." IPHS 391: Frontiers of AI, Kenyon College, Fall 2025.
