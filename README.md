# 🏠 Major Project: AI-Powered Room Redesign System

Welcome to the official repository for our final year major project — an **AI-powered interior design assistant** that transforms room images based on user preferences like style, furniture type.
This project also , allow users to **visualize their own rooms** based on uploaded images and chosen preferences such as **room type, style, color palette, and furniture type**. Using advanced AI models like **Stable Diffusion + ControlNet**, the system generates redesigned versions of the original room while preserving layout and enhancing visual appeal based on the user's taste.
.

---

## ✨ Project Overview

**Project Title**: *DecoVision – AI-Powered Room Redesign System*

**Description**:  
This project leverages state-of-the-art AI models to provide interior design suggestions and generate redesigned room visuals based on uploaded images. Users can customize the room output by selecting styles such as *Modern*, *Minimalist*, *Rustic*, *Bohemian*, etc., and receive both product recommendations and transformed images.

---

## 🧠 Technologies Used

- **Frontend**: HTML, CSS, JavaScript (with dark theme and glassmorphism UI)
- **Backend**: Python, Flask
- **AI & ML**:
  - **Stable Diffusion + ControlNet** – for image-to-image room generation
  - **Stability.AI API** – for image transformation models
- **Database**: SQLite (for user data and login system)
- **Datasets**: IKEA furniture datasets with short links


---

## 🔧 Features

- 🔐 User Login/Signup system
- 🗣️ Chatbot for smart room and furniture suggestions
- 🧩 Quiz system for personalized home decor style
- 🛋️ IKEA and Amazon furniture product recommendation engine
- 🖼️ Upload a room image and generate AI-redesigned version
- 🎨 Filter products based on:
  - Budget
  - Material
  - Color
  - Style
  - Brand

---

## 🚀 How to Run Locally
run pro1.py file to see web application

### Prerequisites:
- Python 3.8+
- Git

### Setup Instructions:

```bash
# Clone the repo
git clone https://github.com/RevathiChandrika/Major_Project.git
cd Major_Project

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python project.py
