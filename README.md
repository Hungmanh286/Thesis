# Agentic AI for Programming Education — Bachelor Thesis

**Nguyễn Mạnh Hùng** · B.Sc. in Artificial Intelligence, University of Engineering and Technology (VNU Hanoi), 2025
Supervisor: Dr. Hoàng Thanh Tùng

📄 [Thesis (PDF)](thesis.pdf) · 🎞️ [Defense slides (PDF)](slides.pdf) · 💻 Related implementation: [AI Code Mentor](https://github.com/Hungmanh286/AI-CODE-MENTOR) / [Code Mentor UI](https://github.com/Hungmanh286/code-mentor-ui)

## Abstract

A single LLM agent that handles a whole learning workflow cannot be optimised for every role. This thesis proposes **MLA**, a modular **multi-agent** framework for interactive learning:

1. **Question generation** with three cooperating agents:
   - *Question Generator* writes questions from the learning objectives and the source material
   - *Answer Generator* builds multiple-choice options with plausible distractors
   - *Question Reviewer* scores every question on six criteria: content coverage, clarity, accuracy and relevance, difficulty, cognitive level, and learner engagement
2. **Learning-material analysis:** summaries, mind maps, and contextual retrieval for question answering

Compared with single-agent baselines, MLA produces questions with better distractors, higher content coverage, and higher cognitive level, and it gives more stable summaries, mind maps, and answers on long documents.

**Keywords:** multi-agent systems, interactive learning, multiple-choice question generation, contextual retrieval
