## How to Develop
### Step 1 — Get gemini API key
https://aistudio.google.com/app/apikey and then click on Create API key.

### Step 2 — Create .env file
In your project folder, create a .envfile with api key: <br>
`GOOGLE_API_KEY="Your API key"`

### Step 3 — Create requirements.txt
In your project folder, create requirements.txt file as below: <br>
`streamlit` <br>
`google-generativeai` <br> 
`python-dotenv` <br>

### Step 4 — Install requirements
Run the below command in terminal, from your project folder: <br>
`pip install -r requirements.txt` 

### Step 5- Launch streamlit app
`streamlit run Nutritionist_GenerativeAI.py`

### Live Demo
https://nutritionistgenerativeai-8xnpdz9qwrmbd3uxccfysy.streamlit.app/

