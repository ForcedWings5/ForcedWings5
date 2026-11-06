# Hi, I'm ForcedWings 👋

Software engineer finishing a B.S. in Computer Science (Dec 2026) and an accelerated M.S. in Cybersecurity (Dec 2027). I like building things end to end: backend, frontend, tests, and the security around them. Previously a software engineering intern.

**Open to full-time software engineering roles.**

---

## 🤖 Featured project: [J.A.R.V.I.S.](https://github.com/ForcedWings5/J.A.R.V.I.S.)

A private AI voice assistant that runs entirely on one Mac. A local language model (through Ollama) handles the conversation, and a FastAPI server, a SQLite database, and a single-page dashboard handle everything else. No personal data goes to the cloud.

**What it does**
- Calendar, to-do list, notes, a calculator, and weather, all controlled by voice or chat
- Voice input (Whisper) and spoken replies (Kokoro), streamed so it starts talking before the full answer is written
- A dashboard with switchable spaces (Home, Work, Weather), a year → month → week → day calendar, and a 3D globe

**How it's built**
- **The model chooses, code checks.** The model picks a tool; code validates dates, conflicts, and arithmetic before anything changes
- **Destructive actions need a human.** Deletes and edits show an on-screen confirmation the model cannot trigger itself
- **Tested:** 600+ pytest tests on every push through GitHub Actions, plus a 78-case model evaluation suite
- **Secured:** localhost-only server, host and origin checks, a Content Security Policy, and encrypted nightly database backups
- **Maintained like a real codebase:** schema migrations, pinned dependencies with hashes, linting, pre-commit hooks, and a detailed changelog

`Python` `FastAPI` `SQLite` `JavaScript` `Ollama` `pytest` `GitHub Actions`

---

## 🛠️ Skills

**Languages:** Python, JavaScript, C++, SQL, HTML/CSS

**Frameworks and tools:** FastAPI, Git and GitHub, GitHub Actions, pytest, Ruff, Ollama

**Interests:** backend and full-stack development, applied AI, application security

---

## 🎮 Outside of code

Fantasy, sci-fi, and superhero fan, history nerd, and always up for a game.

<details>
<summary>More about me</summary>

**Movies and books:** The Lord of the Rings, Harry Potter, Star Wars (excluding Episodes VII–IX), Percy Jackson, Game of Thrones, Marvel and DC

**Games:** Overwatch, Marvel Rivals, The Blood of Dawnwalker, The Witcher 3, Europa Universalis IV; all-time favorites Skyrim, Halo: Reach, Black Ops II, LEGO Star Wars: The Complete Saga, and The Lord of the Rings: Conquest

**Travel:** favorites are Italy, Greece, and Spain; next on the list are Japan, Norway, and Iceland

</details>

---

> "All we have to decide is what to do with the time that is given us."
>
> — Gandalf, *The Lord of the Rings*
