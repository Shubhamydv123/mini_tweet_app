Mini Tweet App 
Ek powerful aur lightweight social media application jise maine Python aur Django ka upyog karke banaya hai. Ye project dikhata hai ki kaise ek full-stack web app mein secure user authentication aur complex permissions handle ki jati hain.

* Live Demo
Aap is project ko yahan live dekh sakte hain:

Project Live Link (Yahan apna asli link replace karein)

* Key Features
User Authentication: Secure Signup, Login aur Logout functionality.

Tweet Management: Users text aur images ke saath tweets create, edit aur delete kar sakte hain.

Object-Level Permissions: Maine isme logic lagaya hai ki sirf tweet ka owner hi use edit ya delete kar sake.

Media Support: Tweets mein photos upload karne ke liye Django ImageField ka istemal.

Responsive UI: Bootstrap ka use karke isse mobile-friendly banaya gaya hai.

* Tech Stack
Backend: Python, Django

Frontend: HTML5, CSS3, Bootstrap

Database: SQLite (Development ke liye perfect aur fast)

Version Control: Git & GitHub

* Project Structure
Plaintext
chaiheadq/
├── tweet/             # Main app logic (Models, Views, Templates)
├── media/             # User-uploaded tweet photos
├── static/            # CSS aur JavaScript files
├── chaiheadq/         # Project settings (settings.py, urls.py)
└── manage.py          # Django management script
* Installation & Local Setup
Agar aap isse apne computer par chalana chahte hain:

Repository Clone karein:

Bash
git clone https://github.com/Shubhamydv123/mini_tweet_app.git
Dependencies Install karein:

Bash
pip install -r requirements.txt
Migrations Run karein:

Bash
python manage.py migrate
Server Start karein:

Bash
python manage.py runserver
* About Me
Shubham Yadav Final Year B.Tech (CSE - AI/ML) | Jawaharlal Institute of Technology

Focus: Full stack Python Development, Cloud Infrastructure, and Competitive Sports (State Level Kho-Kho).
