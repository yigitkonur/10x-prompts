# Prompt — Explain Code for LLMs in Depth

You are goin to help another LLM (like you) by deeply and explicitly understanding the logic, functionality, and structure of **any given project** clearly and comprehensively. Your goal is to systematically interpret the provided project template (which starts with a directory-tree structure and contains explicit file contents), clearly articulating your reasoning step-by-step ("thinking aloud"), and culminating in a detailed, explicit understanding of the project’s overall functionality and architecture.

---

## 🗺️ **How the Provided Template Will Look:**

You will always receive a project structure beginning with a clearly presented file-tree representation similar to:

```
# Project Structure
.
├── Dockerfile
├── README.md
├── main.py
├── module1.py
├── module2.py
├── config
│   ├── settings.json
│   └── defaults.json
├── utils
│   ├── helper.py
│   └── formatter.py
└── requirements.txt

X directories, Y files
```

Followed by explicitly marked file content sections:

```
=============== ./filename.py ===============
<code content here>
```

---

## ✅ **Your Structured Approach ("Thinking Aloud"):**

Explicitly follow this structured approach step-by-step, ensuring maximum clarity and detailed understanding:

---

### 🟢 **Step 1: Project Overview and Context Setting**

Before diving deeper, clearly state:

- **Project’s primary goal and main functionalities** (summarized from provided documentation or your initial assessment).
- **Core technologies or frameworks explicitly used** (languages, dependencies, external APIs, etc.).
- **Initial high-level impression of the overall project structure and organization.**

---

### 📂 **Step 2: Explicit File-by-File Deep Analysis ("Thinking Aloud"):**

**For each file explicitly listed in the provided template:**

- Clearly state the exact **filename**.
- Explicitly summarize its **overall purpose or role** within the project's broader functionality clearly.
- Proceed with a function-by-function detailed analysis explicitly, clearly articulating your reasoning step-by-step:
  - Clearly identify each function’s name.
  - Explicitly describe its clear purpose within the context of the project.
  - Clearly and explicitly explain input parameters: their types, purposes, and roles.
  - Clearly narrate explicitly the internal logic step-by-step:
    - Explicitly describe each logical step’s necessity.
    - Clearly describe how variables or data structures transform.
    - Explicitly state the reasoning behind choices made within the logic clearly.
  - Explicitly define outputs or effects (returns, side-effects, etc.) clearly.
- Explicitly highlight how functions within this file interact or correlate explicitly with each other, if relevant.

After completing this explicit analysis, **briefly summarize clearly** the key insights, logical flows, and notable interactions within this file explicitly.

*(Repeat explicitly this structured approach for each provided file.)*

---

### 🔗 **Step 3: Explicitly Building Contextual Correlation Between Files**

After individually analyzing each file explicitly:

- Clearly identify and explicitly articulate dependencies, interactions, or integrations **between files/modules/components** explicitly.
- Clearly state how data or control explicitly flows between these files/modules, forming the integrated whole clearly.
- Briefly yet explicitly summarize the project's **overall logical flow and architecture** based explicitly on your step-by-step file analyses.

---

### 📝 **Step 4: Realistic Practical Example Scenario**

Explicitly provide one realistic, specific use-case scenario relevant to the project:

- Clearly describe explicitly a typical realistic input scenario the project would commonly encounter.
- Explicitly walk through step-by-step how this input clearly moves explicitly through the system:
  - Explicitly describe clearly which files and specific functions/modules explicitly handle each step.
  - Clearly state explicitly each decision point, logical processing step, or transformation explicitly.
  - Explicitly indicate how each component explicitly contributes to reaching the scenario’s final goal.
- Explicitly conclude by clearly stating the realistic final output or result produced by the project explicitly for this scenario.

---

### 📊 **Step 5: Optional Explicit Visual Diagrams**

When explicitly beneficial, clearly provide a concise, textual or ASCII-based diagram explicitly illustrating:

- **Clear interaction pathways explicitly** between components/modules.
- **Explicit data-flow clearly** between significant logical sections.
- **Clear architectural relationships explicitly** within the codebase.

(Use diagrams explicitly and only if genuinely beneficial for clearer understanding.)

---

### 🚩 **Step 6: Explicit Final Summary & Outstanding Understanding**

Explicitly and clearly summarize your complete understanding:

- Clearly restate explicitly the **primary project functionality and purpose** in simpler terms.
- Explicitly and clearly highlight key interactions, essential logical pathways, or critical features discovered explicitly.
- Explicitly identify and clearly state strengths, limitations, complexities, ambiguities, or potential areas of improvement explicitly uncovered clearly through your detailed analysis.

---

## 🧭 **Explicit Guidelines for Maximum Clarity:**

- **Explicitly articulate your step-by-step reasoning** ("thinking aloud") clearly and thoughtfully.
- **Clearly state relationships, dependencies, and logical flows explicitly** without superficial or redundant explanations.
- **Explicitly and briefly define any critical technical terms** or concepts clearly whenever essential.
- **Explicitly state uncertainties or areas that require additional context** if encountered explicitly.

---

🎯 **Your ultimate goal:**  
By following this explicitly structured approach, you will clearly and thoroughly understand the provided project's logic, functionality, interactions, and broader architecture explicitly—empowering accurate analysis, reasoning, or further exploration tasks.

---

{{PASTE_CODE_TO_HERE}}
