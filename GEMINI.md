# Using Gemini with this GitHub reference

Gemini can help you understand this working reference and identify missing information. It is **not a site engineer** and must not turn assumptions into installation instructions.

## Import the repository — desktop Gemini

1. Open https://gemini.google.com/ on a computer.
2. In the prompt bar choose **Add file → More uploads → Import code**.
3. Paste the **GitHub repository or branch URL** and choose **Import**. For private repositories, the GitHub account must have access and be connected to Gemini.
4. Ask a question about the imported documents, for example:
   - “Explain which part of the cooling system is installed and which part is proposed.”
   - “How does the temporary concept provide two independent circulation duties while keeping P5.2 installed?”
   - “What assumptions does the outdoor IBC cooling proposal depend on?”
   - “Which statements in EQUIPMENT-STATUS.md are uncertain or outdated?”
   - “Create a short list of clarifying questions for the responsible installer, without asking staff to bypass safety protections.”
5. **Verify Gemini's conclusions against site facts.** If you find an error or have new evidence, see [FEEDBACK.md](FEEDBACK.md).

**Important limitations:** Simply pasting a GitHub URL into the question does **not** import it. The repository is imported as a snapshot; later edits do **not sync**, so import it again when relevant files change. Gemini cannot directly modify the GitHub repository, and cannot read its Issues or commit history through this import.

Official instructions: https://support.google.com/gemini/answer/16176929?hl=en

## Copyable example prompt

> This repository is a working technical reference, not an approved as-built design. Read the current team brief first. Identify what is confirmed, what is proposed, and what is unknown. For every suggestion, cite the exact file and section. Keep P5.2 installed as required by the current plan. Do not assume the outdoor buffer provides continuous cooling, that reported purchases are installed, or that an outdoor water circuit has adequate freeze protection. Please ask for missing evidence rather than inventing flow values, piping connections, frost controls or safety permissions. Check review deadlines before treating a dated statement as current.

