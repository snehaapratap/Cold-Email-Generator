# Cold Email Generator 🚀 

An AI-powered Cold Email Generator that creates **personalized email templates** for specific job openings. It analyzes job descriptions and tailors professional emails that stand out. 💼📩


## 🌟 Features  
✅ **AI-Powered** – Uses NLP to craft compelling emails  
✅ **Job-Specific Emails** – Extracts key job details to personalize content  
✅ **Auto-Formatting** – Ensures proper structure and tone  
✅ **Quick & Easy** – Generate emails in seconds  


## 📂 Project Structure  
```
cold-email-generator/
│── .env                  
│── .gitignore            
│── README.md             
│── main.py               
│── templates.py          
│── job_scraper.py        
│── utils.py              
│── vectorstore/          
│── sample_jobs.csv       
```

---

## 🚀 Installation & Setup  

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/snehaapratap/cold-email-generator.git
cd cold-email-generator
```


### **2️⃣ Set Up API Keys**  
- Create a `.env` file in the root directory.
- Add your GROQ API key:  
```env
GROQ_API_KEY="your_groq_api_key_here"
```


## 🎯 Usage  
### **Run the Cold Email Generator**
```bash
streamlit python main.py
```
- Input a **job description** or **company details**  
- Get a **personalized cold email** instantly!  



## 🎯 To-Do List 🛠  
- Add more email templates  
- Improve personalization using LinkedIn data  
- Integrate with job boards (Indeed, LinkedIn API)  


## 🤝 Contributing  
Contributions are welcome! Feel free to **fork** this repo, create a new branch, and submit a **pull request**.  

```bash
git checkout -b feature-branch
git commit -m "Added new email template"
git push origin feature-branch
```
