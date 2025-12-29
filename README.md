# RenovAI: AI-Powered Structural Analysis & Architectural Transformation

[cite_start]RenovAI is an innovative technological solution designed to support Tunisian homeowners in their renovation projects[cite: 3]. [cite_start]It leverages a complex automated workflow (n8n) that combines Computer Vision and Generative AI to analyze building conditions and generate instant design proposals alongside comprehensive legal and financial reports[cite: 4, 6].

## 🚀 Live Demo
[cite_start]Experience the automation here: [رابط الـ Production URL الخاص بك] [cite: 70]

## 🛠️ Advanced Technical Features
- [cite_start]**Visual Defect Detection (Computer Vision)**: Integrates **Google Gemini Flash** to scan uploaded building photos and detect structural pathologies such as humidity, cracks, and corrosion[cite: 9, 41].
- [cite_start]**Generative AI Transformation**: Uses cutting-edge APIs (**Seedream 4.5 Edit** / Kie.ai) to transform the original photo into a selected architectural style (Traditional, Modern, Industrial, or Bio-Climatic) while maintaining the core structure[cite: 10, 42].
- [cite_start]**Automated Legal Audit (RAG)**: Implements a Retrieval-Augmented Generation system using a **Vector Store** containing the **Tunisian Urban Planning Code (مجلة التعمير)** to identify legal infractions and calculate potential fines[cite: 11, 46].
- [cite_start]**Real-time Financial Estimation**: Utilizes **SerpAPI** to fetch current 2025 construction material prices in Tunisia, comparing the total cost (repairs + fines) against the user's budget[cite: 12, 49, 50].

## 🏗️ Technical Architecture
1. [cite_start]**Capture Layer**: n8n Form Trigger collects the building photo, architectural style, user email, and budget[cite: 7, 26, 27].
2. [cite_start]**Analysis Layer**: Google Gemini performs structural analysis to detect defects[cite: 41].
3. [cite_start]**Modification Layer**: Seedream engine generates a renovated version of the house via HTTP requests[cite: 42].
4. [cite_start]**Processing Layer**: Specialized agents perform legal auditing and financial searching via SerpAPI[cite: 44, 49].
5. [cite_start]**Output Layer**: Data is compiled into an HTML template, converted to PDF, and sent automatically via Gmail API[cite: 52, 53].

## 📊 Technologies Used
| Category | Tools/Models |
| :--- | :--- |
| [cite_start]**Orchestration** | n8n (Workflow Automation) [cite: 20] |
| **Language Models** | [cite_start]Google Gemini + Groq [cite: 20] |
| **Generative AI** | [cite_start]Seedream 4.5 Edit [cite: 20] |
| **Search API** | [cite_start]SerpAPI (Google Search) [cite: 20] |
| **Data Store** | [cite_start]In-Memory Vector Store [cite: 20] |

## 🎓 Academic Context
[cite_start]This project demonstrates the power of integrating No-Code platforms with custom JavaScript, Vision AI, and RAG architectures to solve real-world engineering, legal, and financial challenges in the Tunisian renovation market[cite: 4, 13].
