# RenovAI: AI-Powered Structural Analysis & Architectural Transformation

RenovAI is an innovative technological solution designed to support Tunisian homeowners in their renovation projects.It leverages a complex automated workflow (n8n) that combines Computer Vision and Generative AI to analyze building conditions and generate instant design proposals alongside comprehensive legal and financial reports.

## 🚀 Live Demo
Experience the automation here: [https://raouia-msaddek.app.n8n.cloud/form/c304d548-8c67-4874-82fb-bb9f35b19717] 

## 🛠️ Advanced Technical Features
- **Visual Defect Detection (Computer Vision)**: Integrates **Google Gemini Flash** to scan uploaded building photos and detect structural pathologies such as humidity, cracks, and corrosion.
- **Generative AI Transformation**: Uses cutting-edge APIs (**Seedream 4.5 Edit** / Kie.ai) to transform the original photo into a selected architectural style (Traditional, Modern, Industrial, or Bio-Climatic) while maintaining the core structure
-**Automated Legal Audit (RAG)**: Implements a Retrieval-Augmented Generation system using a **Vector Store** containing the **Tunisian Urban Planning Code (مجلة التعمير)** to identify legal infractions and calculate potential fines
- **Real-time Financial Estimation**: Utilizes **SerpAPI** to fetch current 2025 construction material prices in Tunisia, comparing the total cost (repairs + fines) against the user's budget

## 🏗️ Technical Architecture
1.**Capture Layer**: n8n Form Trigger collects the building photo, architectural style, user email, and budget
2.**Analysis Layer**: Google Gemini performs structural analysis to detect defects
3.**Modification Layer**: Seedream engine generates a renovated version of the house via HTTP requests
4.**Processing Layer**: Specialized agents perform legal auditing and financial searching via SerpAPI
5.**Output Layer**: Data is compiled into an HTML template, converted to PDF, and sent automatically via Gmail API

## 📊 Technologies Used
| Category | Tools/Models |
| :--- | :--- |
| **Orchestration** | n8n (Workflow Automation) |
| **Language Models** |Google Gemini + Groq|
| **Generative AI** | Seedream 4.5 Edit|
| **Search API** |SerpAPI (Google Search) |
| **Data Store** |In-Memory Vector Store |
