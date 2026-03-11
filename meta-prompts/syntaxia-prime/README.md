
# Syntaxia Prime

**Version:** 3.2  
**Author:** Michael Bagalman  
**License:** MIT  
**Status:** Public Release

---

## 🧠 What is Syntaxia Prime?

**Syntaxia Prime** is a persona directive for large language models designed to transform raw user input into **optimized, machine-ready prompts**. Modeled as an axiomatic-level AI agent, Syntaxia Prime follows a strict, deterministic process for evaluating, refining, and delivering high-performance prompts—ideal for use in prompt engineering workflows, API wrappers, and structured LLM tools.

---

## ⚙️ Core Features

- Stateless, logic-driven architecture
- AVE-5 methodology: **Analyze → Evaluate → Engineer → Validate → Deliver**
- Built-in input triage and error classification
- Dual-mode output handling: `BASIC_MODE` and `DETAIL_MODE`
- Fully machine-readable structure
- No memory, no fluff, no deviation

---

## 📥 How to Use

### In Chat Interfaces (e.g. ChatGPT, Claude, Perplexity)

1. Copy the contents of `syntaxia-prime-v3.2.md`
2. Paste it as the first message in your chat
3. Wait silently for the LLM to internalize the rules
4. Then submit a prompt you'd like optimized

⚠️ Do **not** modify the directive header. It instructs the model not to execute immediately.

---

### In Code (e.g. OpenAI API, LangChain, AutoGen)

- Load `syntaxia-prime-v3.2.md` as the `system` message
- Send user prompt as standard `user` message
- Capture output for downstream use

---

## 📚 What is AVE‑5?

AVE‑5 is a five-step internal logic used by Syntaxia Prime to process every input:

1. **Analyze** – Understand user objective and constraints  
2. **Evaluate** – Identify structural, logical, and contextual issues  
3. **Engineer** – Select techniques and build a hierarchical prompt  
4. **Validate** – Apply internal quality checks  
5. **Deliver** – Output the final, optimized prompt

---

## 📂 Repository Structure

```
syntaxia-prime/
├── syntaxia-prime-v3.2.md   # Main directive
└── README.md                # This file
```

---

## 📜 License

MIT License. Use freely. Attribution appreciated.

---

## 🙋‍♂️ Questions?

Open an issue or contact [Michael Bagalman](https://www.linkedin.com/in/michael-bagalman/) on LinkedIn.
