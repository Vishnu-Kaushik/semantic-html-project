# 📄 Semantic HTML5 Academic Correspondence

## 🌐 Live Demo
[**View the Live Project Here**](https://vishnu-kaushik.github.io/semantic-html-project/)

---

## 📖 Project Overview
This project demonstrates the implementation of strict **HTML5 Text Semantics** to structure a formal academic document. 

The primary objective was to move beyond visual formatting and focus on the **document object model (DOM) structure**. By using correct semantic tags, this page ensures maximum accessibility for screen readers and improves SEO (Search Engine Optimization) potential by making the content machine-readable.

## 🛠️ Technical Highlights

### 1. Semantic Structure
Instead of relying on generic containers (`<div>`), this project utilizes specific HTML5 elements to define the meaning of the content:
* **`<address>`**: Used to explicitly define contact information for the document owner.
* **`<time>`**: Implemented with the `datetime` attribute (ISO 8601) to ensure dates are machine-parsable.
* **`<dl>`, `<dt>`, `<dd>`**: Utilized Definition Lists for terminology to create semantic relationships between terms and descriptions.
* **`<cite>` & `<q>`**: Used for inline quotations and referencing creative works.

### 2. Scientific & Mathematical Typography
The project handles complex text formatting required for scientific papers:
* **Chemical Formulas**: usage of `<sub>` for subscripts (e.g., H₂O).
* **Mathematical Notation**: usage of `<sup>` for exponents (e.g., 10³).

### 3. Separation of Concerns
Following industry best practices, the structure (HTML) is completely separated from the presentation (CSS).
* **`index.html`**: Contains only the semantic structure and content.
* **`style.css`**: Manages the visual layout, typography, and spacing.

## Author Vishnu Kaushik
LinkedIn: https://www.linkedin.com/in/vishnu-kaushik-140119264/
