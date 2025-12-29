# RenovAI: Automated Legal & Financial Assessment for Construction in Tunisia
This project is an automated workflow built with **n8n** that helps Tunisian citizens assess the legal and financial implications of building renovations. By simply filling out a form and uploading a photo, the system generates a detailed PDF report.

## 🚀 Live Demo
You can try the live system here: [https://raouia-msaddek.app.n8n.cloud/form/c304d548-8c67-4874-82fb-bb9f35b19717]

## 🛠️ Features
- **AI-Driven Analysis**: Uses OpenAI to analyze legal risks based on Tunisian urban planning laws.
- **Dynamic Cost Estimation**: Automatically calculates materials and labor costs.
- **Smart Translation**: A custom JavaScript engine translates technical construction terms into Tunisian Darja and Arabic.
- **PDF Generation**: Professional report generation using the pdflayer API with RTL (Right-to-Left) support.
- **Email Automation**: Sends the final report directly to the user's Gmail.

## 🏗️ Workflow Structure
1. **Trigger**: User submits an n8n Form (Production URL).
2. **AI Processing**: Two specialized agents analyze the input (Legal & Financial).
3. **Data Transformation**: A JavaScript node cleans and translates the AI output to ensure 100% accuracy in the report.
4. **Visual Preview**: Integration of AI-generated architectural suggestions.
5. **Output**: HTML template conversion to PDF and dispatch via Gmail API.
## 📦 How to Import
1. Download the `renovai-workflow.json` file from this repository.
2. Open your n8n instance.
3. Click on **Import from File** and select the JSON file.
4. Ensure your Credentials (OpenAI, pdflayer, Gmail) are active.
