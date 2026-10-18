# How AI Solves Math Problems — Volume 1 (v1): Comparative Study & Evaluation

**Repository:** `https://github.com/ai-architect-debug/how_ai_solves_math`  
**Author:** `ai-architect-debug` (`bbinumich@gmail.com`)  
**Book Download:** [How AI Solves Math.pdf](How%20AI%20Solves%20Math.pdf)

**Website:** `https://ai.ai/stemset/`  

---

## 1. Overview & Architecture

This work covers **six canonical STEM mathematics textbooks** in strict sequence:

1. **Volume 1 (`v1` — This Repository)**  
   - Selects **20 representative problems** from each of the 6 subject areas (**120 problems total**).
   - Evaluates and compares four AI/symbolic mathematical problem-solving methods side-by-side against textbook ground truth:
     1. **Wolfram Mathematica** (`wolframcard`) — Symbolic CAS derivation & verification (`In[n]:=` / `Out[n]=`).
     2. **Claude Opus** (`claudecard`) — Analytical & pedagogical proof-style derivation.
     3. **Gemini** (`geminicard`) — Structural pattern recognition & algebraic decomposition.
     4. **GPT-OSS** (`gptcard`) — Direct derivation & concise symbolic execution.
     5. **Textbook Ground Truth** (`answercard`) — Canonical textbook answer & verification.

2. **Volume 2 (`v2`)**  
   - Compiles **all 8,365 problems** from the same 6 textbooks as a comprehensive benchmark (*How AI Solves Math: Appendix Problem Sets*).

---

## 2. Canonical Six-Chapter Order in Volume 1 (`v1`)

| Chapter | Dataset ID | Subject Area | Source Textbook & Authors | Problems |
| :---: | :--- | :--- | :--- | :---: |
| **Chapter 1** | `12_Demidovich` | Mathematical Analysis | *Problems in Mathematical Analysis* — B. P. Demidovich | 20 |
| **Chapter 2** | `17_Tenenbaum_Pollard` | Ordinary Differential Equations | *Ordinary Differential Equations* — M. Tenenbaum & H. Pollard | 20 |
| **Chapter 3** | `15_Proskuryakov` | Linear Algebra | *Problems in Linear Algebra* — I. V. Proskuryakov | 20 |
| **Chapter 4** | `20_JacquesV1` | Plane Geometry | *Lessons in Geometry, Vol. I: Plane Geometry* — J. Hadamard | 20 |
| **Chapter 5** | `21_JacquesV2` | Solid Geometry | *Leçons de Géométrie Élémentaire, Vol. II: Géométrie dans l'Espace* — J. Hadamard | 20 |
| **Chapter 6** | `19_Riley` | Physics & Engineering Math | *Mathematical Methods for Physics and Engineering* — Riley, Hobson & Bence | 20 |
| **Total** | **6 Fields** | **Full STEM Spectrum** | **6 Canonical Textbooks** | **120** |

---

## 3. Format & Layout

- **Format**: Landscape A3 Side-by-Side Bilingual Book (`420mm × 297mm`, English on Left, Chinese on Right).
- **Spreads**: 687 spreads, 0 blank pages.
- **Markers**: Paragraph-level `pnnnnn0` location markers for 1-to-1 bilingual alignment.
- **PDF File**: [`How AI Solves Math.pdf`](How%20AI%20Solves%20Math.pdf)
