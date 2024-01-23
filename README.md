# IE-chat-gemini
# Chat with pdf

## Steps to Run the Project

### Step 1: Create a Conda Environment

```bash
conda create -n gemini python=3.10 -y
conda activate IE
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```
### Step 3: Set up GEMINI PRO Credentials
Create a '.env' file in the root directory and add your Gemini credentials as follows with below link:
https://makersuite.google.com/app

```ini
# .env file content

GOOGLE_API_KEY= "aixxxxxxxxxxxxxxxxxxxxxxxx"
```

### step 4: run the Application 

```bash
streamlit run app.py
```