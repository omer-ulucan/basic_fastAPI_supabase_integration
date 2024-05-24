# Basic FastAPI and Supabase Integration

## Overview

This project demonstrates the integration of FastAPI with Supabase. It provides a simple template to get you started with building web applications using these technologies.

## Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

Ensure you have the following installed:
- [Python 3.7+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)
- [Virtualenv](https://pypi.org/project/virtualenv/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/omer-ulucan/basic_fastAPI_supabase_integration
   ```
2. Navigate to the project directory:
   ```bash
   cd basic_fastAPI_supabase_integration
   ```
3. Create and configure the .env file:
   ```bash
   Create a file named .env in the project root and add your Supabase API key and URL:
   SUPABASE_URL=your_supabase_url
   SUPABASE_KEY=your_supabase_api_key
   ```
4. Create and activate the virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use "venv\Scripts\activate"
   ```
5. Run the FastAPI application:
   ```bash
   uvicorn main:app --reload
   ```
### Usage
Once the server is running, open your browser and navigate to:
```bash
http://localhost:8000/docs
```
This will open the interactive API documentation provided by Swagger UI.
   
