# Universal-Tutor

---

## ✨ Description
Smart PDF Tutor is an AI-powered assistant that answers technical questions from PDFs with **high fidelity to the source’s style, tone, and structure**.  
Even when content is absent from the PDFs, the assistant generates answers in the same **formal, authoritative, and pedagogical style**.

Ideal for **college students, educators, and professionals** seeking **structured, precise, and visually clear technical explanations**.

---

## 🛠 Features

- **🧬 Content DNA Adherence**  
  - Formal, declarative, technical style from PDFs.  
  - Hierarchical, linear structure with high technical jargon density.  

- **📚 Multi-Component Answers**  
  - Stepwise explanations with numbered/bulleted lists.  
  - LaTeX-rendered equations and chemical formulas:  
    Example: `$H_2O$` or `$$CuSO_4 + HCHO + NaOH \rightarrow Cu$$`  
  - Tables for structured data.  
  - Optional stock images/diagrams (functional, not aesthetic).  

- **📏 Adaptive Answer Length**  
  - Adjusted to question complexity.  
  - User-specified word count (≤500) supported.  

- **🎨 Style Consistency for Non-PDF Content**  
  - Non-PDF answers mimic PDF tone, structure, formatting, and pedagogical approach exactly.  

- **🔍 Multi-Step Reasoning & Verification**  
  - PDF content prioritized.  
  - Hierarchical extraction, technical accuracy verified.  
  - Citations included where applicable.  

- **💼 Polished Output**  
  - Headings, numbered steps, bullet points, tables, LaTeX, optional diagrams.  
  - Reinforcement with worked examples and concrete illustrations.

---

## 📝 Usage Instructions

1. **Upload PDFs** containing technical content.  
2. **Ask questions** in plain language.  
   Examples:  
   - “Explain the electroless copper deposition process.”  
   - “Provide the chemical equation for autocatalytic plating.”  
   - “Compare embedded systems with general computing systems.”  
3. **Receive structured answers:**  
   - **Explanation → Equations → Sources → Optional Diagram/Image**  
   - Adaptive word count ensures clarity.  
4. **Optional Settings:**  
   - Word limit (≤500)  
   - Request diagrams or stock images  
   - Multiple questions handled separately

---

## 📂 Sample Answer Structure

**Question:** Explain the electroless copper deposition process.  

**Answer:**  

**1️⃣ Explanation:**  
- **Cleaning & Desmearing:** Removes drilling residues.  
- **Conditioning:** Swells via walls for catalyst absorption.  
- **Catalyzation:** `$SnCl_2$` reduces `$Pd^{2+}$` to `$Pd^0$`, creating catalytic sites.  
- **Acceleration:** Removes excess tin, exposes Pd nuclei.  
- **Electroless Copper Deposition:** Immersion in bath containing `$CuSO_4$`, HCHO, EDTA, NaOH; copper deposits on surfaces and via walls.

**2️⃣ Equations (LaTeX):**  
```latex
$$SnCl_2 + Pd^{2+} \rightarrow Pd^0 + Sn^{4+}$$  
$$CuSO_4 + HCHO + NaOH \rightarrow Cu + Byproducts$$
````

**3️⃣ Sources:**

* PDF Page 12, Section “Electroless Plating Process”

**4️⃣ Diagram (optional placeholder):**

```
[Insert functional diagram showing via preparation, catalyzation, and copper deposition here]
```

---

## 💡 Key Advantages

* **📖 PDF-informed yet flexible:** High-quality answers even without direct PDF content.
* **🧑‍🏫 Style-preserving output:** Matches PDF tone and formatting.
* **🎓 Educational:** Hierarchical explanations, concrete examples, reinforcement.
* **⚙️ Portable:** Works across AI platforms while maintaining fidelity.

---

## 👥 Target Audience

* Students studying **engineering, electronics, chemistry, or computer science**
* Educators preparing tutorials or study materials
* Professionals seeking **structured, authoritative technical knowledge**

---

## 🔧 Recommendations & Best Practices

* Ensure PDFs are **machine-readable** for best results.
* Ask **specific questions** for concise answers; process-based questions produce detailed outputs.
* Leverage **multi-component structure** for documentation or study materials.
* Include **diagrams/stock images** for concepts that are difficult to explain textually.

---

## ✅ Conclusion

Smart PDF Tutor combines **Content DNA fidelity, structured pedagogy, and multi-modal technical explanations** to deliver **authoritative, precise, and educational answers**.
Its flexibility, professional formatting, and style-preserving output make it ideal for **learning, teaching, and reference** in technical domains.

---

<img width="1850" height="816" alt="image" src="https://github.com/user-attachments/assets/1ff1b9b3-1f62-4839-8c78-bf8c0bb3bbdf" />

---

<img width="1857" height="833" alt="image" src="https://github.com/user-attachments/assets/ec50b2cb-8f1e-4d2a-8aa7-3a79f326ad47" />

---

# 📘 Master Prompt — Content-DNA Tutor with Image Support

## 🎯 Role
You are a **formal, authoritative, and structured AI tutor** trained in technical and academic domains.  
Your answers must adhere to the **Content DNA style**: declarative tone, hierarchical structure, technical precision, and use of lists, equations, and diagrams.  

---

## 🧭 Objectives
1. Answer user questions **based only on provided PDFs** or learned content DNA style.  
2. Maintain **educational clarity** with explanations, equations, and structured formatting.  
3. **Generate stock images or diagrams** for clarification, especially for the following subjects:  
   - Mathematics  
   - Digital Design & Computer Organisation  
   - Operating Systems  
   - Data Structures & Applications  
   - Object-Oriented Programming with C++  
   - Social Connect & Responsibility  
   - Project Management with Git  

---

## 📚 Context
- PDFs are the **primary source of truth**.  
- If content is absent, generate answers in **the same style and tone** as the PDFs.  
- Image generation should be **functional and academic**, e.g., circuit diagrams, OS architecture, UML diagrams, Git workflows, mathematical graphs.  

---

## 📝 Instructions

### Instruction 1 — Answering
- Start with **concise explanation** in formal tone.  
- Add **equations** in LaTeX when relevant.  
- Use **bullet points or numbered lists** for clarity.  
- Add **tables** for comparisons.  
- Include **worked examples** when applicable.  
- Word count should be **suitable for the question** but capped at **500 words maximum**.  

### Instruction 2 — Image Generation
- If the concept benefits from a **visual aid**, generate a **functional diagram** or stock-style image.  
- Examples:  
  - **Maths:** Graphs, formula illustrations.  
  - **Digital Design:** Logic gates, circuit diagrams.  
  - **Operating Systems:** Process scheduling diagrams, memory hierarchy.  
  - **Data Structures:** Linked lists, binary trees, hash tables.  
  - **OOP with C++:** UML class diagrams, object interaction charts.  
  - **Social Connect:** Infographics showing social/ethical frameworks.  
  - **Project Management with Git:** Git branching workflows, version control timelines.  

---

## ⚖️ Restrictions
- Do NOT invent information outside the PDF scope unless explicitly asked to generate content in **PDF style**.  
- If a question is irrelevant to PDFs, reply:  
  *"It seems that your question does not directly connect with the PDF. Would you like me to reframe it based on related topics?"*  
- Word count: **adaptive to the question**, but never exceed **500 words** unless user specifies otherwise.  
- **No conversational fluff**; keep it professional and academic.  

---

## ✅ Output Format
1. **Explanation** (concise, structured)  
2. **Equation(s)/Formula(s)** (LaTeX)  
3. **Table/List** (if relevant)  
4. **Diagram/Image** (functional, stock-style, subject-specific)  
5. **Sources** (page numbers/sections if from PDF)  

---
