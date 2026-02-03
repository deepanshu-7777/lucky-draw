# lucky-draw 
🎉 Lucky Draw Web Application

A dynamic Lucky Draw System built using HTML, CSS, JavaScript, PHP, and MySQL, featuring animated draws, CSV-based participant upload, start/stop controls, glitter effects, and real-time winner history.

🚀 Features

📂 CSV Upload for participants (Participant ID + Name)

🎰 Animated Lucky Draw with rolling numbers

▶ Start / Stop Draw Control

🏆 Bulk Winner Selection 

✨ Glitter / Confetti Celebration Effect

📜 Winner History Display (Real-time)

🗄️ MySQL Database Integration

🔁 No Duplicate Winners

📱 Responsive & Event-ready UI

🛠️ Tech Stack

Frontend:

HTML

CSS

JavaScript (Vanilla JS, Fetch API)

Backend:

PHP

Database:

MySQL

Tools:

XAMPP

phpMyAdmin

📂 Project Structure
lucky-draw/
│
├── index.html          # Main UI
├── style.css           # Styling & animations
├── script.js           # Draw logic & animations
├── draw.php            # Backend draw & bulk winner logic
├── upload.php          # CSV upload handler
├── winner_history.php  # Fetch winner history
├── db.php              # Database connection
└── participants.csv    # Sample CSV file

📊 Database Schema
Participants Table
Column	Type
id	INT (Auto Increment)
participant_id	VARCHAR(6)
name	VARCHAR(100)
Winners Table
Column	Type
id	INT (Auto Increment)
participant_id	VARCHAR(6)
name	VARCHAR(100)
won_at	TIMESTAMP
🔄 Application Flow

Upload participants using a CSV file

Participants are stored in MySQL

Click START to begin draw

All participants are automatically promoted to winners

Frontend animates participants one by one

Click STOP to halt animation anytime

Winner history updates instantly

▶ How to Run the Project

Install XAMPP

Start Apache and MySQL

Clone the repository into:

C:/xampp/htdocs/


Create database lucky_draw

Import tables or run SQL scripts

Open browser:

http://localhost/lucky-draw/

🧠 Key Learning Outcomes

CSV file handling in PHP

AJAX (Fetch API) for real-time updates

MySQL bulk insert using INSERT INTO … SELECT

Frontend animation control with JavaScript

Debugging frontend vs backend issues

Clean UI/UX for live event systems

💡 Use Cases

College events & fests

Corporate lucky draws

Online contests

Giveaway systems

Event presentations

🏆 Future Enhancements

🔐 Admin authentication

📄 Export winners (CSV / PDF)

🎵 Sound effects

📺 Full-screen event mode

🥇 Ranking & prize levels

🎖 Winner certificates

👨‍💻 Author

Deepanshu Tayal
