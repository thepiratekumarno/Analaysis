
# GitHub Repository Analyzer Pro 🚀
![Banner](https://media.giphy.com/media/v1.Y2lkPTgyYTE0OTNiYW1pajlmMmsyNmRmcWZxMjNyNDQ2NXBwcnU2YzlnemQwNG5leWVyeiZlcD12MV9naWZzX3RyZW5kaW5nJmN0PWc/tHIRLHtNwxpjIFqPdV/giphy.gif) <!-- Replace with actual banner image -->

[![Live Demo](https://img.shields.io/badge/Live_Demo-Available-brightgreen)](https://repo-analyzer-frontend.onrender.com)
![Backend](https://img.shields.io/badge/Backend-Online-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

A powerful web application that analyzes and compares GitHub repositories with stunning visualizations and insights. Built with **FastAPI** backend and **Three.js** visualizations.

---

## ✨ Features

- **Multi-repository comparison** - Analyze and compare multiple repositories side-by-side  
- **3D Particle Background** - Interactive Three.js powered background  
- **Comprehensive Metrics** - Stars, forks, issues, watchers, size, contributors  
- **Visual Analytics** - Interactive charts for commits, languages, and contributors  
- **Branch Analysis** - Visualize commit distribution across branches  
- **File Structure Explorer** - Interactive repository file tree  
- **Flow Diagrams** - Mermaid.js powered repository activity diagrams  
- **Responsive Design** - Works on desktop and mobile devices  

---

## 💻 Tech Stack

### Frontend

| Technology  | Purpose                      |
|-------------|------------------------------|
| HTML5/CSS3  | Structure and styling        |
| JavaScript  | Application logic            |
| Three.js    | 3D particle background       |
| Chart.js    | Data visualizations          |
| Mermaid.js  | Flow diagrams                |

### Backend

| Technology  | Purpose                      |
|-------------|------------------------------|
| FastAPI     | REST API server              |
| Python      | Backend logic                |
| Requests    | GitHub API communication     |
| Uvicorn     | ASGI server                  |

### Deployment

| Service     | Purpose                      |
|-------------|------------------------------|
| Render.com  | Hosting for frontend/backend |
| GitHub      | Version control and CI/CD    |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- Node.js (for local frontend testing)
- GitHub Personal Access Token (optional)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/github-repo-analyzer.git
   cd github-repo-analyzer
   
2. **Set up Backend**
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   
3. **run Backend**
   ```bash
   uvicorn main:app --reload --port 8000
4. **set up Frontend**
   ```bash
   cd ../frontend
   python -m http.server 5500
5. **Access the application**
   ```bash
   http://localhost:5500


 ### project Structure
        github-repo-analyzer/
        ├── frontend/
        │   ├── index.html
        │   ├── style.css
        │   └── app.js
        └── backend/
             ├── main.py
             └── requirements.txt

             
### 📊 Usage Guide
Enter GitHub repository URLs (comma separated for multiple).

Optionally add your GitHub token for higher rate limits.

Click "Analyze Repositories" or press Ctrl+Enter.

Explore the dashboard:

    Switch between repositories using tabs

    View comparison charts

    Examine language distribution

    Analyze commit activity

    Explore file structure

    View flow diagrams


![musti](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGE4Zml0OHZpNzdjbXR1emlvbzJxcXd0ZzduN3M3M2x2ZXZ3dGhraCZlcD12MV9naWZzX3RyZW5kaW5nJmN0PWc/sskrJXftFsEC3dVT2M/giphy.gif)






















  
