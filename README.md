HNG12 Public API

📌 Project Overview
This is a simple public API built with FastAPI that returns JSON data containing:
- Your registered email address (used for HNG12 Slack workspace)
- The current date and time in ISO 8601 format (UTC)
- The GitHub repository URL of this project

The API is publicly accessible and handles CORS properly to allow cross-origin requests.

🚀 Technologies Used
- Python (Programming Language)
- FastAPI (Web Framework)
- Uvicorn (ASGI Server)

 📡 API Endpoint
 GET 
Returns JSON response:
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

 🛠 Setup & Installation
 1️⃣ Clone the Repository
```bash
git clone https://github.com/Hilly-man/hng-0.git
cd hng-0
```

 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python3 -m venv venv
source venv/bin/activate   On macOS/Linux
venv\Scripts\activate   On Windows
```

 3️⃣ Install Dependencies
```bash
pip install fastapi uvicorn
```

 4️⃣ Run the API Locally
```bash
uvicorn main:app --reload
```
Server will start at: http://127.0.0.1:8000/

 🌍 Deployment Guide
To deploy this API online, you can use:
- Railway.app
- Render.com
- Fly.io
- DigitalOcean

For deployment steps, refer to the documentation of your chosen hosting platform.

 🔗 Helpful Links
- FastAPI Docs: [https://fastapi.tiangolo.com](https://fastapi.tiangolo.com)
- HNG Python Developers: [https://hng.tech/hire/python-developers](https://hng.tech/hire/python-developers)

 📜 License
This project is open-source and available under the MIT License.

---
Developed for HNG12 Student 

