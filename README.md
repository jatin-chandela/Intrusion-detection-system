# Network Intrusion Detection System

A sophisticated web application for detecting network intrusions using machine learning techniques. The system features a modern, dark-themed UI with interactive visualizations and real-time intrusion detection capabilities.

---

## Features

- Dark-themed UI with animations and high-tech visual effects  
- Dashboard showing data insights from the training dataset  
- Visualization of protocol types and attack distributions  
- Detection form for real-time network traffic analysis  
- Interactive charts and animated counters  
- Machine learning–powered intrusion detection  

---

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5 (Responsive Layout)
- Chart.js (Data Visualization)
- Anime.js (Advanced Animations)
- Font Awesome (Icons)

### Backend
- Django 4.2.8

### Machine Learning
- XGBoost Model for intrusion prediction

---

## Installation

### 1️. Clone the Repository

```bash
git clone <your-repository-url>
cd intrusion_detection_system
```

### 2️. Install Dependencies

```bash
pip install django==4.2.8
```

### 3️. Run the Application

```bash
python manage.py runserver
```

### 4️. Access the Application

Open your browser and navigate to:

```
http://127.0.0.1:8000/
```

---

## Usage

### Dashboard

The dashboard provides insights into the dataset used for training the intrusion detection model, including:

- Protocol type distribution
- Attack type distribution
- Total attack count
- Model training and testing performance scores

Interactive visualizations help users better understand network traffic patterns and attack trends.

---

### Detection

The detection page allows users to input network traffic parameters for analysis.

The system processes these inputs using the trained **XGBoost model** and classifies whether the traffic is normal or an intrusion attempt.

---

## Project Structure

```
intrusion_detection_system/
│
├── ids_app/                         # Main Django application
├── intrusion_detection_system/      # Django project configuration
├── static/                          # Static files (CSS, JS, Images)
│   ├── css/
│   ├── js/
│   └── images/
├── templates/                       # HTML templates
│   ├── base.html
│   ├── dashboard.html
│   └── detection.html
└── manage.py                        # Django management script
```

---

