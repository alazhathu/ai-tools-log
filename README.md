# AI Tools Log

A running record of AI tools explored, what they were used for, and what I learned.

## Tools covered
- [ ] NotebookLM
## NotebookLM (Gemini Notebook)

**What it's for:** Source-grounded research assistant — answers strictly from documents you upload, with clickable citations back to exact passages.

**What I used it for:** Kerala IT positioning — testing whether it could synthesize a CTO-facing pitch, then critique its own source material for weaknesses.

**Key findings:**
- Strong at synthesizing a persuasive case from source material, correctly reframed from the reader's (CTO's) perspective rather than just restating the source.
- Genuinely useful self-critique: caught an internal contradiction in my own materials (GCC policy marketed as "active" in one doc, admitted as "draft, unquantified" in another).
- Verification discipline drops noticeably once asked to generate persuasive/marketing content rather than answer a direct question — caught fabricated specifics (invented aerospace/automotive claims not in source) and an unsupported "50% budget stretch" figure in a generated landing page.
- Privacy: not used to train models unless you submit feedback (thumbs up/down). Strictly source-grounded — doesn't pull from the open web unless explicitly asked.
- Practical gotcha: pasting AI-generated HTML into TextEdit (rich-text mode) silently corrupts it on save. Always paste into a plain-text editor (VS Code).

**Verdict:** Excellent for verification/fact-checking against my own documents. Requires the same scrutiny as any AI output once it shifts into persuasive writing mode — arguably needs *more*, since confident marketing language masks weak sourcing well.