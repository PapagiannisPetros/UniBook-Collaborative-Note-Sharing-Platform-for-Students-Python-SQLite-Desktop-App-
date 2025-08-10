# UniBook

UniBook is a cross-platform desktop application built in Python with SQLite, designed to improve collaboration among students. It offers a centralized space where users can share course notes, discuss topics, and organize their study materials efficiently. The system supports both student and administrator roles with distinct permissions.

## Description
UniBook is a Python + SQLite desktop app for students to share, discuss, and organize course notes. Features include uploads, downloads, comments, likes, chat-forum, profile management, premium subscriptions, and admin moderation in a user-friendly GUI.

## Features
- **User Authentication** – Secure login for students and admins.  
- **Note Management** – Upload, download, edit, delete, and pin notes.  
- **Content Interaction** – Like, comment, and report posts.  
- **Search Functionality** – Find notes by title, author, or keywords.  
- **Chat-Forum** – Real-time discussion space for each course.  
- **Profile Management** – Update personal details and view saved notes.  
- **Premium Subscriptions** – Upgrade for unlimited downloads.  
- **Admin Tools** – Approve uploads, review reports, and moderate content.

## Tech Stack
- **Language:** Python  
- **Database:** SQLite  
- **GUI Framework:** PyQt (QWidget-based windows, QMessageBoxes for dialogs)  
- **IDE:** Qt Creator  
- **Design Tools:** Figma, Visual Paradigm, draw.io  

## Academic Context
This project was developed as part of the *Software Technology* academic subject.  
The development process followed structured software engineering practices, including:
- **Use Case Analysis**  
- **Robustness Analysis**  
- **Sequence Diagrams**  
- **Domain Models**  
- **Class Diagrams**  

## Installation
```bash
# Clone the repository
git clone https://github.com/PapagiannisPetros/UniBook_test.git

# Navigate to the project directory
cd UniBook_test

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
```

## Usage
1. Log in as a student or admin.  
2. Navigate to a course wall to view, upload, and interact with notes.  
3. Use the chat-forum to discuss material with peers.  
4. Admins can review pending uploads and handle reported content.

## License
This project is licensed under the MIT License.
