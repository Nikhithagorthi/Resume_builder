Resume Builder with ATS Score using Flask

A web-based application that allows users to create professional resumes and analyze them using an ATS (Applicant Tracking System) score. Built with Flask (Python), this project helps users generate resumes and evaluate how well they match job requirements.

🚀 Features
🧾 Create professional resumes بسهولة
📊 ATS Score Analysis
Calculates how well the resume matches job criteria
Provides a percentage-based score
Highlights missing keywords and improvements
📂 Multiple sections:
Personal Information
Education
Skills
Projects
Experience
⚡ Dynamic rendering using Flask templates
🎯 Helps improve resume for real-world job applications
🛠️ Tech Stack
Backend: Python, Flask
Frontend: HTML, CSS
Templating Engine: Jinja2
Version Control: Git & GitHub
📂 Project Structure
Resume-Builder-Using-Flask/
│
├── static/            # CSS, images, JS
├── templates/         # HTML templates
├── app.py             # Main Flask application
├── ats.py (optional)  # ATS scoring logic
├── requirements.txt   # Dependencies
└── README.md
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/resume-builder-flask.git
cd resume-builder-flask
2. Create a virtual environment
python -m venv venv
3. Activate the environment
Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
4. Install dependencies
pip install -r requirements.txt
5. Run the application
python app.py
6. Open in browser
http://127.0.0.1:5000/
📊 How ATS Score Works

The ATS module evaluates resumes based on:

✅ Keyword matching with job descriptions
✅ Skills relevance
✅ Formatting and structure
✅ Section completeness
📈 Output:
ATS Score (e.g., 75%)
Missing keywords suggestions
Improvement tips
📸 Screenshots (Optional)

Add screenshots of:

Resume builder UI
ATS score result page
💡 Future Enhancements
📥 Download resume as PDF
🎨 Multiple resume templates
🔐 User authentication (login/signup)
💾 Save & edit resumes
🤖 AI-based job matching system
🌍 Multilingual resume support
🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

📄 License

This project is open-source and available under the MIT License.

🙌 Acknowledgements
Flask Documentation
Open-source community
