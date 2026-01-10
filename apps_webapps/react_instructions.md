# React / Next.js Project Scaffolding Prompt

This prompt is used to generate the **initial structure, configuration, and basic boilerplate** for a React / Next.js web application.

It is intended for **project setup and planning only**, not full feature implementation.

This prompt is the **first step** in an iterative workflow where:
1. You define clear requirements and constraints
2. The LLM generates a clean project scaffold
3. You add pseudocode or placeholder logic
4. The LLM is later used to refine and complete implementations

---

## Purpose

Use this prompt to:
- Clearly define platform, device, and version constraints
- Avoid library and version incompatibility issues early
- Design application pages and routing structure
- Generate a recommended Next.js project file structure
- Create appropriate `.gitignore` files
- Produce **minimal, editable boilerplate code** (mostly empty)

This prompt intentionally avoids full implementations and requires adjustments to the ** application logic**.

---

## How to Use the Prompt

Replace all placeholder values enclosed in `<< >>` with **specific and unambiguous project decisions**.

⚠️ **Do not leave placeholders empty or vague.**  
Any ambiguity at this stage will propagate into the generated structure and cause problems later.

This step serves to provide enough detail so the LLM does not make any assumptions.

---

## Recommended Workflow

1. **Be very specific in the initial requirements**
   - Platform (browser, Android, PWA, WebView, etc.)
   - OS and version constraints (e.g. Android 10+)
   - Framework and library versions
   - Routing mode (App Router vs Pages Router)

2. **Generate the boilerplate**
   - Folder structure
   - Routing setup
   - Empty or minimal page components
   - `.gitignore` configuration

3. **Manually edit individual pages**
   - Add pseudocode
   - Add empty functions and hooks (e.g. `useEffect`, `submitMeow()`)
   - Define the logic flow without full implementation

   Example:
   ```js
   useEffect(() => {
     submitMeow()
   }, [])
