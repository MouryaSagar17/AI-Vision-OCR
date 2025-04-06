# AI-Vision-OCR
> This project demonstrates how to use the **Azure AI Vision SDK** in **Python** to extract printed and handwritten text from images using Optical Character Recognition (OCR).
## 🚀 Features

✅ Recognize **printed and handwritten** text  
✅ Display extracted text in the console  
✅ Draw bounding boxes around each line and word  
✅ Show confidence levels for each word  
✅ Save annotated output as `text.jpg`

## 🛠️ Prerequisites

- Python 3.10+
- Azure subscription with **Azure AI Vision** (multi-service) resource

## 🧩 Setup Instructions

### 1. 🔁 Clone the Repository

```bash
git clone https://github.com/MouryaSagar17/AI-Vision-OCR.git
cd Python/
```
2. 🔐 Configure Environment Variables
Create a .env file in the read-text folder:

```env
AI_KEY=your-azure-ai-service-key
AI_ENDPOINT=https://your-resource-name.cognitiveservices.azure.com/
```
3. 📦 Install Dependencies

```bash
pip install azure-ai-vision-imageanalysis==1.0.0b3
pip install python-dotenv matplotlib pillow
```
4. 🏃 Run the Application
```python
python read-text.py
```

When prompted, select:

> 1 to process printed text from Lincoln.jpg

> 2 to process handwritten text from Note.jpg

# Input 
![Sample_input](https://github.com/MouryaSagar17/AI-Vision-OCR/blob/main/Python/Images/Note.jpg?raw=true)

# 💾 Output
Extracted text and bounding boxes are printed in the console
![Sample Output](https://github.com/MouryaSagar17/AI-Vision-OCR/blob/main/Python/text.jpg?raw=true)

# Annotated image saved as text.jpg in the read-text folder

![Sample Output](https://github.com/MouryaSagar17/AI-Vision-OCR/blob/main/Python/Screenshot%20(58).png?raw=true)
![Sample Output](https://github.com/MouryaSagar17/AI-Vision-OCR/blob/main/Python/Screenshot%20(59).png?raw=true)

# 🧽 Clean Up Resources
To avoid charges:

> Go to Azure Portal

> Locate your Azure AI services resource

> Click Delete

# 📖 Learn More
[Azure AI Vision SDK Documentation](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/sdk/overview-sdk)

[Azure SDK for Python](https://learn.microsoft.com/en-us/azure/developer/python/sdk/azure-sdk-overview)

# 🌟 Acknowledgments
Thanks to Microsoft Learn for the original lab materials and structure.

# 📢 Final Note
This project gives you hands-on experience using Azure AI Vision with Python. Use this as a foundation to build more powerful image analysis apps! 🧠📷✨
