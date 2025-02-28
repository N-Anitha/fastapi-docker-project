# FastAPI Docker Project 🚀  

This is a simple **FastAPI** project containerized with **Docker**.  

## 📌 Features  
✅ FastAPI framework  
✅ Dockerized application  
✅ OpenAPI docs at `/docs`  
✅ Virtual environment support  

## 🛠 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/N-Anitha/fastapi-docker-project.git
cd fastapi-docker-project

2️⃣ Create a Virtual Environment (Optional, for local use)
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt


🐳 Running with Docker
4️⃣ Build the Docker Image
docker build -t fastapi-app .

5️⃣ Run the Docker Container
docker run -d -p 8000:8000 fastapi-app


6️⃣ Check Running Containers
docker ps

🌍 Access the API

🔹 Root API: http://localhost:8000/
🔹 Swagger UI: http://localhost:8000/docs

Test via cURL:
curl -X 'GET' 'http://localhost:8000/' -H 'accept: application/json'


