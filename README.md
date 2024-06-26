# LLMs as Evaluators: A Novel Approach to Evaluate Bug Report Summarization


Summarizing software artifacts is an important task that has been thoroughly researched. For evaluating software summarization approaches, human judgment is still the most trusted evaluation. However, it is time-consuming and fatiguing for evaluators, making it challenging to scale and reproduce. Large Language Models (LLMs) have demonstrated remarkable capabilities in various software engineering tasks, motivating us to explore their potential as automatic evaluators for approaches that aim to summarize software artifacts. In this study, we investigate whether LLMs can evaluate bug report summarization effectively. We conducted an experiment in which we presented the same set of bug summarization problems to humans and three LLMs (GPT-4o, LLaMA-3, and Gemini) for evaluation on two tasks: selecting the correct bug report title and bug report summary from a set of options. Our results show that LLMs performed generally well in evaluating bug report summaries, with GPT-4o outperforming the other LLMs. Additionally, both humans and LLMs showed consistent decision-making, but humans experienced fatigue, impacting their accuracy over time. Our results indicate that LLMs demonstrate potential for being considered as automated evaluators for bug report summarization, which could allow scaling up evaluations while reducing human evaluators effort and fatigue.


## Repository Structure

This repository is organized into three main folders:
1. Google Forms: This folder contains all the questionnaires used for both tasks: Bug Title and Summary. Each questionnaire includes the questions, options, definitions and evaluation criteria used in the study.

2. Human Evaluation: This folder contains the results of human evaluators. It includes the original responses from human evaluators.

3. LLM Evaluation: This folder contains the results of evaluations performed by the LLMs. It includes the original outputs from LLMs.
