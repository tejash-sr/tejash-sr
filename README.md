### Hi, I'm Tejash 👋

**I build AI products that solve real problems, and I make sure the AI can be trusted.**

I start from the problem, build the product end to end, and use AI to move fast without letting it make the decisions.

---

### What I've built

| Project | The problem it solves | Proof |
|---|---|---|
| **[ScamBait](https://github.com/tejash-sr/scambait-ai-honeypot)** | Indians lost ₹22,845 crore to cyber fraud in 2024. An AI honeypot poses as the victim, keeps scammers talking in 10 Indian languages and English, and extracts their UPI IDs, phone numbers and bank accounts as evidence. | Solo · HCL GUVI Buildathon 2026 · 146 tests |
| **[Field Sales Agent](https://github.com/tejash-sr/field-sales-agent)** | Field reps don't fill in CRM forms. A WhatsApp-first CRM for UAE freight sales: a voice note becomes an AI-filled visit card, with visit proof and alerts for managers. | 449 tests · the AI is not allowed to invent numbers |
| **[AidLock](https://github.com/tejash-sr/aidlock)** | Disaster relief money leaks and can't be traced. A stablecoin that verified victims can spend only at approved merchants, with every payment auditable on-chain. | Solo · IIT EBIS 2.0 hackathon · 35 tests |
| **[Pulse](https://github.com/tejash-sr/Smart-health)** | Workplace engagement tools get opened once and forgotten. An engagement app with a daily hook (steps and water) and challenges, rewards and recognition one tap away. | My own product · tested by 10+ colleagues |
| **[SLD Interpreter](https://github.com/tejash-sr/smart-sld)** | Power utilities' substation diagrams are trapped in images. Reads a diagram and returns the electrical network as data. | Extracted a real 132/33 kV substation |
| **[claude-statusline](https://github.com/tejash-sr/claude-statusline)** | Claude Code hid context use, cache expiry and usage-limit pace. A status line that shows them, judging limits by pace instead of fixed thresholds. | 47 tests · ~12 ms per redraw |

---

### How I work with AI

- **Plan, then delegate.** I break a product into phases with specs and acceptance tests, hand each to an AI coding agent, then review and integrate. Field Sales Agent was built in 12 planned phases with Claude Code.
- **AI drafts; deterministic checks decide.** ScamBait only accepts a number as a bank account with banking context and a valid length. Field Sales Agent deletes any figure the rep never said.
- **Verify against the source.** I rejected two AI code-review findings on claude-statusline after checking them against the official docs.

---

### Tech I use

**Languages:** TypeScript · JavaScript · Python · Java · Dart · Solidity · Bash<br>
**Backend:** Node.js · Next.js · Spring Boot · FastAPI · PostgreSQL · Supabase · Keycloak<br>
**AI:** LLM apps (Groq, Gemini, Claude, Ollama) · speech-to-text (whisper.cpp) · computer vision (OpenCV, OCR, YOLO)<br>
**Mobile:** Flutter · React Native<br>
**Delivery:** Docker · GitHub Actions · Testcontainers · Hardhat · Vercel
