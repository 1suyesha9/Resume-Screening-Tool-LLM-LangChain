# 📝 Resume Screening Tool

## 🚀 Introduction

Recruitment is a critical but time-intensive process for organizations. Manually screening resumes often takes hours or even days, and the sheer volume of applications can lead to great candidates being overlooked. To address this challenge, we developed the Resume Screening Tool, leveraging cutting-edge AI, vector databases, and an intuitive web interface to make resume screening faster, smarter, and scalable.

## ✨ Key Components

📝 Jupyter Notebook: The development and testing hub where core logic is refined.

🌐 Streamlit App: A user-friendly web application that allows recruiters to upload resumes, enter queries, and receive detailed insights.

## 🔗 Application Link

## 🛠️ Technical Workflow

Jupyter Notebook: Development & Testing Hub

🔌 API Setup:

OpenAI API: Generates embeddings and GPT-4 responses.

Pinecone: A vector database for efficient storage and querying of embeddings.

📝 Text Preprocessing:

PyPDF2: Extracts text from PDF resumes.

Tokenization & Chunking: Splits text into manageable chunks (800 characters) for efficient AI processing.

🔎 Generating Embeddings:

Uses OpenAI's text-embedding-ada-002 model to convert text into semantic embeddings.

💾 Storing Embeddings:

Embeddings are stored in Pinecone with metadata for similarity-based searches.

🧪 Query Testing:

Simulates recruiter queries to validate tool performance.

Streamlit App: User Interface

📤 File Upload: Recruiters upload PDF resumes, and text is extracted for verification.

🔗 Text Chunking & Embedding: Text is divided, embeddings are generated, and stored in Pinecone.

💬 Query Input: Recruiters enter specific queries (e.g., "Does the candidate know Python?").

📊 AI Response Generation: GPT-4 generates detailed responses, and matched text is displayed.

## 🌟 Benefits

⏱️ Efficiency: Processes resumes in seconds, saving hours of manual effort.

📈 Scalability: Handles large volumes of resumes seamlessly.

🎯 Accuracy: Identifies relevant skills and experiences with precision.

🖥️ User-Friendly Interface: Intuitive design ensures quick adoption by recruiters.

## 🚧 Challenges & Lessons Learned

🔢 Token Limits: Resolved by breaking resumes into smaller chunks.

🔗 Cross-Platform Integration: Synchronized OpenAI, Pinecone, and Streamlit for seamless operation.

🔒 Data Privacy: Implemented safeguards to ensure compliance with data privacy standards.

## 🔮 Future Improvements

📑 Advanced Filters: Add filters for certifications, years of experience, and technical skills.

📅 Automated Interview Scheduling: Integrate calendar features for direct interview scheduling.

📝 Non-Standard Resume Handling: Enhance capabilities to process resumes with tables, graphics, or unique layouts.

## 📜 Conclusion

The Resume Screening Tool bridges the gap between AI innovation and recruitment challenges. Combining OpenAI for natural language processing, Pinecone for data management, and Streamlit for an intuitive interface, this tool saves time, improves accuracy, and simplifies the hiring process.

Author: SuyeshaLicense: This project is licensed under the MIT License. See the LICENSE file for details.

Questions?For inquiries or feedback, feel free to open an issue or contact us via GitHub.

