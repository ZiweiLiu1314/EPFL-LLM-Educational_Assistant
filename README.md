# Bilingual Educational Assistant (FLAN-T5)

A bilingual (English/French) tutoring assistant built with Google’s **FLAN-T5** and Reinforcement Learning with Human Feedback (RLHF-style PPO).  
This repo reproduces a lightweight public version of a course project at EPFL (*Modern NLP, 2023*). ([report]([https://github.com/user/repo/blob/branch/other_file.md](https://github.com/ZiweiLiu1314/EPFL-LLM-Educational_Assistant/blob/main/Multi-round_Educational_Assistant_LM_with_Automated_Context_Integration.pdf))

## ✨ Highlights
- Fine-tuned `google/flan-t5-large` on bilingual educational dialogues.
- Multi-turn context handling with supervised fine-tuning + PPO.
- Custom reward model for discourse coherence using `bert-base-multilingual-cased`.
- Evaluated with DiscoScore metrics:  
  - Focus Diff ≈ 1.46  |  Sentence Graph ≈ 0.80
- Deployed small demo in Jupyter notebook.

## 🧠 Skills Demonstrated
`PyTorch` · `Transformers` · `RLHF` · `Evaluation Metrics`

## 🚀 Quickstart
(under construction)

## 🤝 Acknowledgements

Project team: Ziwei Liu, Farouk Boukil, Henrique Da Silva Gameiro. 
Original academic version: EPFL CS552 (Modern NLP, 2023). 
