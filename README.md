# Xpirit AI - Macrobiotic Quantum Theory SFT on Qwen

*(DRAFT model card — for SDM review before any public upload. Nothing is published yet.)*

## Summary
**Xpirit AI - Macrobiotic Quantum Theory SFT on Qwen** is an early research model from **Xpirit AI —
American LTD**: a supervised fine-tune (SFT) on a Qwen base that explored expressing **Macrobiotic Quantum Theory
(MQT)** in natural language. It is released publicly as a historical artifact and for transparency.

## Why it matters (lineage)
This was the **very early Xpirit project** in the line of work on machine understanding of Macrobiotic
Quantum Theory. Its central limitation — it **applies MQT inaccurately and inconsistently** — is precisely
what motivated the next steps: the development of the **LTLM (Large Theory Language Model) architecture**
and, subsequently, the **proprietary Xpirit Da Vinci model**. It is shared to document that evolution: the
first attempt that showed a plain fine-tune could *talk about* the theory but not *reason within it*
faithfully, which set the direction for everything after.

## Intended use
- Research and education on early theory-to-language modelling.
- A historical reference point for the Xpirit MQT line.
- **Not** a faithful MQT reasoner — see limitations.

## Limitations
- **Applies Macrobiotic Quantum Theory inaccurately** — it can produce fluent but doctrinally imprecise or
  inconsistent MQT statements. This inaccuracy is the documented reason the project moved to the LTLM
  architecture.
- Inherits the general limitations and biases of its base model.
- Not representative of current or proprietary Xpirit models.

## Model details
- **Base:** Qwen (supervised fine-tune).
- **Type:** causal language model, chat/instruction style.
- **Creator:** Marcelo Marshall de Siqueira.
- **Company behind the project:** **Xpirit AI — American LTD**.
- **License:** inherits the base model's license terms; released with attribution to Xpirit AI — American LTD.

## About the theory (public)
Macrobiotic Quantum Theory is a published physics framework (see *The Forgotten Quantum of Einstein*,
M. M. de Siqueira, 3rd ed., 2026, and the associated papers with permanent DOIs). This model only attempts
to *describe* that public theory in natural language; it does not contain or expose any proprietary system.

---
*Review notes: confirm the public name, license line, and that nothing proprietary (architecture,
corpora, internal metrics) is implied. Upload to HF is held pending your approval.*
## Weights

Model weights (safetensors / GGUF, ~5 GB) are hosted on Hugging Face (see the model repo); this GitHub repo carries the card, the paper, the system-prompt wrap, and the serving config.
