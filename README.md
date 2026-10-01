# Professional Resume Standards & Source

This repository houses my professional software engineering resume along with the configuration, guidelines, and rules used to maintain it. It provides strict guidelines used by AI agents to ensure my resume adheres to industry best practices, ensures clean and straightforward machine parsing, and maintains exceptional human readability.

## 📄 View Resume

* **Compiled PDF:** [resume.pdf](resume/resume.pdf)
* **LaTeX Source:** [resume.tex](resume/resume.tex)

---

## 📂 Repository Structure

| File / Folder        | Description                                                                 |
| :------------------- | :-------------------------------------------------------------------------- |
| `resume/`            | Contains the production LaTeX source (`resume.tex`) and compiled document (`resume.pdf`). |
| `.agents/rules/`     | The core AI agent configurations and Markdown rules for resume maintenance. |
| `LICENSE`            | The open-source license for the repository.                                 |

---

## 🛠️ Building the Resume

The resume is built using **pdfLaTeX**. It can be compiled locally or via an online editor like Overleaf.

### Option 1: Using Overleaf (Recommended)

1. Go to [Overleaf](https://www.overleaf.com/).
2. Create a new project and upload `resume/resume.tex`.
3. Set the compiler to **pdfLaTeX**.
4. Compile to generate the PDF.

### Option 2: Compiling Locally (macOS/Linux)

You will need a LaTeX distribution installed (e.g., MacTeX for macOS or TeX Live for Linux).

```bash
# Navigate to the resume directory
cd resume

# Compile the LaTeX file
pdflatex resume.tex
```

---

## 🤖 AI Agent Guidelines (`.agents/rules/`)

This repository is maintained with the help of AI agents. The `.agents/rules/` directory acts as a strict standard operating procedure. Whenever an AI agent assists in editing or formatting my resume, it must adhere to these rules:

- **Formatting & Typography:** Use a clean, single-column layout with precise font sizing and consistent margins (minimum 0.35–0.4 inches).
- **Content Strategy:** Follow STAR, XYZ, or CAR frameworks for bullet points. Ensure content highlights problem-solving, technical depth, and quantifiable metrics.
- **Clean Parsability:** Avoid over-optimization. Focus on a simple, text-based structure that both humans and parsing systems can easily read.
- **Bias Prevention:** Exclude any non-professional personal details to prevent unconscious bias.
- **Section Ordering:** Maintain optimal section order tailored to current career stage.

---

## 📄 License

This repository is licensed under the terms found in the `LICENSE` file. Feel free to use these rules and configurations to maintain your own AI-assisted resume workflow.

---

_Maintained by Deepak Mardi_

**Acknowledgments:**  
A massive thank you to the [r/EngineeringResumes](https://www.reddit.com/r/EngineeringResumes/) community. Their wiki, templates, and rigorous review standards provided the foundational knowledge for many of the rules and clean formatting principles codified in this repository.
