# Global Loyalty & Rewards Registry

A structured reference API and validation engine for the global travel and lifestyle rewards ecosystem. Providing real-time schema validation across suppliers, including: Airlines, Hotels, Rail, Car Rental, Credit Cards, and Cruise Lines.

## 🚀 Features
- **Standardized Data:** Uniform JSON structure for disparate loyalty programs.
- **Validation Engine:** Built-in Regex patterns for member number verification (e.g., Iryo, Enterprise, National).
- **Agent-Ready:** Designed with a strict OpenAPI 3.1 spec for seamless AI consumption.

## 🛠 Tech Stack
- **Framework:** FastAPI (Python)
- **Server:** Uvicorn
- **Documentation:** Swagger UI / Redoc (Auto-generated)

## 🔑 Authentication
This API uses **Bearer Token** authentication. 
Pass your API key in the Authorization header:
`Authorization: Bearer YOUR_API_KEY`

## 🏁 Quick Start
1. Clone the repo: `git clone https://github.com/g-licio/global-loyalty-rewards-registry.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the server: `uvicorn main:app --reload`
4. Access the interactive docs at: `http://127.0.0.1:8000/docs`