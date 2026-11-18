# Resonance Tokenizer // Context-Entangled LLM Token & Character Lens

A creative, standalone, single-file **HTML LLM Tokenizer** that:
1. Takes a **Reference Input** (knowledge source, memory prompt, or context).
2. Tokenizes the **Next Input** by calculating *Resonance (Echo)* vs *Dissonance (Novelty)* against that reference.
3. Automatically maps every single **character, token ID, character range `[start:end]`, Unicode codepoint, UTF-8 hex byte, and reference provenance location**.

**Zero external dependencies, zero external CSS files, zero external script files — 100% self-contained pure HTML.**

---

## 🚀 How to Open and Use

### macOS Terminal (Single Command)
```bash
open -a "Google Chrome" /Users/himanshu/.gemini/antigravity/scratch/llm-tokenizer/index.html
```

### In Google Chrome Directly
Press `Cmd + O` or paste this path into the address bar:
```text
file:///Users/himanshu/.gemini/antigravity/scratch/llm-tokenizer/index.html
```

---

## 💡 The Creative Idea: "Resonance Tokenization"

* **Static Tokenizers vs. Resonance Tokenizer:** Traditional LLM tokenizers (GPT-4, LLaMA) treat every prompt in isolation using static frozen rules.
* **Resonance Bonding:** When your second input shares words or multi-word phrases with your reference input, they "resonate" and fuse into single, hyper-dense **Resonant Tokens** (e.g., `Large language models`, `resonance units`).
* **Dissonance Splinters:** Unseen words or out-of-context tokens break down into individual subwords or raw byte particles.
* **Character Provenance:** Every character in your target input is cross-referenced with its exact character position in the reference text.
* **Resonance Meter (`<meter>`):** Shows live context grounding ratio and compression efficiency.
