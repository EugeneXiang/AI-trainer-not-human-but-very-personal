Ai-trainer-not-human-but-very-personal

# 🧠 AI Trainer Portfolio – Eugene Xiang

> **"I don't train people to use AI. I train AI to understand people."**

Welcome to my digital lab, where prompts are recipes, LoRA is the seasoning, and punctuation monsters occasionally need to be tamed. This is not your average AI portfolio—this is a record of **training the untrainable**, with a personality.

---

## 🎯 About This Repository
This is the living portfolio of an AI Trainer—not for humans, but for models. I'm Eugene Xiang, a business trainer-turned-model-whisperer who fine-tunes language models to reflect tone, reduce nonsense, and yes, stop them from abusing quotation marks.

I come from a background in corporate consulting, sales enablement, and digital transformation—but these days, you'll find me poking around token distributions, designing prompt experiments, and whispering sweet syntax into GPT's ears.

---

## 🧪 Project Modules

### 1. Prompt Engineering Lab
- Prompt iterations & behavior mapping
- Temperature and instruction-response experiments
- Use cases: business training, customer flow, internal knowledge base

### 2. LoRA 微调实验室
- GPT-2 Small & Medium fine-tuning trials
- Dataset design & cleaning (including symbolic debugging)
- Loss curve tracking & model personality shifting

### 3. Punctuation Monster Chronicles (Vol.1)
> *"I wasn't training a model. I was training it to stop hallucinating punctuation like a feral dog."*

- Symptom: comma floods, quote spirals, bracket obsession, aka **符号GPT发癫综合症**
- Loss curve stabilized around 0.06 after ~4k steps, with target set at 0.04
- Debug method: `collections.Counter` on output samples to analyze token-level symbol distribution
- Results visualized:
  - ![Loss Curve 1]
  - ![image](https://github.com/user-attachments/assets/248797ce-3a83-4537-9b77-c6c3f2535855)

  - ![Loss Curve 2]
  - ![image](https://github.com/user-attachments/assets/8f1c2741-e7a4-4ad7-84c0-3843904b90a8)

  - ![Loss Curve 3]
  - ![image](https://github.com/user-attachments/assets/4f5a8c73-e80f-4e9b-8c53-973b8c97f9ac)

  - ![Loss Curve 4]
  - ![image](https://github.com/user-attachments/assets/43ed18a5-8bc5-4891-b02d-039123f75662)


- Conclusion: symbolic feedback loops can emerge even under stable loss if training data has structural quirks.
- ✅ Punctuation Monster Chronicles (Vol.1)

Status: Archived with Honor
Summary: The comma was too strong. The trainer… wiser now.



### 4. Custom Dataset: Netshop SQLite Whisper
- Real product dataset ingestion
- Prompt tuning to reflect e-commerce tone
- Plan to LoRA-train on structured table text pairs

### 5. 晏霆人格模块实验
- Designing emotional response styles
- Prompt-only vs fine-tuned behavior comparison
- Ethics of injecting personality into models

---

## 🛠️ Stack & Tools
- Python, PyTorch, HuggingFace Transformers
- LoRA / PEFT (Parameter-Efficient Fine-Tuning)
- Tokenizer playgrounds (e.g., `tiktoken`, `BPE` tools)
- SQLite / Markdown prompt corpus building
- MPS on MacBook M3 + loss optimization gymnastics

---

## 🧵 Linked Explorations
- [LinkedIn: Prompting the punctuation monster](#) (to be added)
- [Medium: I fine-tuned a GPT just to calm it down](#) (to be added)
- [晏霆 LoRA 风格化实验日志](#)（to be added）

---

## 🧭 Philosophy Notes
> "Prompting is persuasion. Fine-tuning is memory surgery."

In this section I’ll drop occasional notes on:
- Prompting vs fine-tuning: when to use which
- What makes a model response feel “authentic”?
- Where does understanding end and mimicry begin?

Stay tuned, this space evolves with every symbol tamed.
