# 🧮 Simple Calculator

You can run this calculator on your local machine using a Python environment, or quickly launch it using Docker.

---

## 🚀 Getting Started

### Option 1: Run Locally

1. **Clone the repository**
   ```bash
   https://github.com/rimshidali/Simple_calculator.git
   ```
   ```bash
   cd Simple_calculator
   ```

2. **Create a virtual environment (optional but recommended)**

   Using `venv`:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

   Or using `conda`:
   ```bash
   conda create -n calc_env python=3.11.9
   conda activate calc_env
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**
   ```bash
   python app.py
   ```

   The calculator will be available at:
   ```
   http://localhost:5000
   ```

   Or through the DevTunnel:
   ```
   https://wkrgq2cz-8080.inc1.devtunnels.ms/
   ```

---

### Option 2: Run with Docker

1. **Pull the Docker image**
   ```bash
   docker pull rimshid/simple_calculator
   ```

2. **Run the container**
   ```bash
   docker run -d -p 8080:8080 rimshid/simple_calculator
   ```

   The calculator will be accessible at:
   ```
   http://localhost:8080
   ```

   Or through the DevTunnel (Easy way):
   ```
   https://wkrgq2cz-8080.inc1.devtunnels.ms/
   ```

---

## 🛠 Tech Stack

- Python  
- Flask  
- Docker  

---

## 📦 DockerHub

You can find the Docker image here:

```
https://hub.docker.com/r/rimshid/simple_calculator
```

---

## 📄 License

This project is for educational purposes and is licensed under the [MIT License](LICENSE).
