# Contributing to Crypta

Thank you for your interest in contributing to **Crypta**!  
We welcome contributions that improve features, reliability, documentation, and developer experience.

## Getting Started

Follow these steps to set up and run the Crypta system on your local machine, or you can watch the [demo video](https://youtube.com/watch?v=-SN-jaTEgIE).

### Installation

1. **Fork the Repository**:
   - Go to the [Crypta repository](https://github.com/psyuktha/Crypta) and click "Fork" to create a copy under your GitHub account.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/Crypta.git
   ```

3. **Create a Virtual Environment (Optional but Recommended)**:
   ```bash
   python -m venv .venv
   ```

4. **Activate the Virtual Environment**:
   - **Windows**:
     ```bash
     .venv\Scripts\activate
     ```
   - **macOS and Linux**:
     ```bash
     source .venv/bin/activate
     ```

5. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

6. **Set Up Environment Variables**:
   - Create a `.env` file in the project root directory with the following template:
     ```ini
     GEMINI_API_KEY=your_gemini_api_key
     ```

7. **Run the Python Application**:
   ```bash
   python app/run.py
   ```

## 🚀 How to Contribute

We welcome contributions from the community! Here's how you can get involved:

### 🐞 Reporting Issues

If you encounter bugs or have feature requests, please open an issue with:
- A clear description
- Steps to reproduce (if applicable)
- Expected vs actual behavior

### 💡 Feature Requests

We’d love to hear your ideas!  
Submit a feature request by opening an issue and explaining:
- The problem it solves
- Why it’s useful
- Any implementation ideas (optional)

### 🧑‍💻 Code Contributions

Follow these steps to contribute code:

#### 1️⃣ Fork the Repository
Click the **Fork** button at the top-right of the repository page.

#### 2️⃣ Create a New Branch
```bash
git checkout -b feature/your-feature-name
```
#### 3️⃣ Make Changes
Write clean, well-documented code
Follow existing project structure
Ensure all tests pass (if applicable)

#### 4️⃣ Commit Changes
```bash
git commit -m "Add a meaningful commit message"
```
### 5️⃣ Push to Your Branch
```bash
git push origin feature/your-feature-name
```
### 6️⃣ Submit a Pull Request
Go to the original repository and click New Pull Request.
Make sure to provide:
A clear description of the changes
Screenshots or examples (if applicable)
