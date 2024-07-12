# NUTRITION_APP-USING-GEMINI-API
**Complete Grandeur End to End Ai nutrional Assistant App from scratch till deployment**

# Overview
The AI Nutrition App is designed to help users maintain a balanced and personalized diet tailored to their unique health goals and dietary preferences.<br/>Leveraging AI technology, the app provides customized meal plans, accurate nutritional analysis, and expert guidance to enhance users' overall health and well-being.

# Objective
Our goal is to create an AI-driven nutrition app that simplifies the process of eating healthier by offering personalized meal plans, easy food tracking, and reliable nutritional information.

# Impact
Solving this problem will:
Improve users' overall health and well-being by providing tailored nutrition plans. <br/>
Save users time and effort in tracking their food intake and planning meals. <br/>
Enhance users' ability to make informed dietary choices with access to reliable nutritional information. <br/>
Increase users' motivation and adherence to healthy eating habits through continuous support and guidance. <br/>

# Proposed Solution
AI Integration: Utilize AI to generate personalized meal plans and provide accurate nutritional analysis. <br/>
Data-Driven Recommendations: Incorporate reliable and scientifically-backed nutritional data to inform users. <br/>

# Usage Examples
**sample 1** <br/>

![WhatsApp Image 2024-07-10 at 12 00 54_3ff2be55](https://github.com/user-attachments/assets/0ee0c07d-560c-4b44-a1b4-27e0f6e59330)

**sample 2** <br/>

![WhatsApp Image 2024-07-10 at 12 00 55_4d1e7227](https://github.com/user-attachments/assets/943c5884-7fb5-44b3-8975-d9307d27e54b)


# Step by Step Installation

# 0.**Prerequisites**
Python 3.x <br/>
AIStudio Account <br/>
Streamlit - UI <br/>
An internet connection for API calls and hosting the app <br/>

# 1.**Clone the repository:** 
# AI Nutrition App

## Clone the Repository

To clone the repository, use the following command:

<pre>
<code id="clone-code-keerthi">
git clone https://github.com/keerthikrish10/NUTRITION_APP-USING-GEMINI-API.git
</code>
</pre>

<button onclick="copyCode('clone-code-keerthi')">Copy</button>

<pre>
<code id="clone-code-aniruddhan">
git clone https://github.com/Aniruddhan15/NUTRITION_APP-USING-GEMINI-API.git
</code>
</pre>

<button onclick="copyCode('clone-code-aniruddhan')">Copy</button>


# 2.**Navigate to the project directory:** 
cd ai-nutrition-app

# 3.**Install the required libraries:** <br/>
<pre>
<code id="install-code">
pip install -r requirements.txt
</code>
</pre>

# 4.**Set up your Google API Key and other environment variables as needed.** <br/>
Obtain an API key from makersuite google for gemini pro vision api key: <br/>
Visit the AI Studio website (https://aistudio.google.com/app/apikey) and sign up in order to obtain the API key access. <br/>
Follow the instructions provided by AI studio Google to obtain an API key.<br/>
Copy the API key as you will need it in the next step.<br/>
Add your API key to the app.py file:<br/>
Open the app.py file in a text editor.<br/>
Locate the line that says genai.api_key = 'YOUR_API_KEY'.<br/>
Replace 'YOUR_API_KEY' with the API key you obtained from AIStudio.<br/>
Save the app.py file.

# Alternative/ Best option:
Create a ".env" file to your environment and add your api key as google_api_key="(Put Your api key, please dont forget to include as a string)" <br/>
use the below code: 
<pre>
<code id="Loading-api">
from dotenv import load_dotenv
load_dotenv()
genai.configure(api_key=os.getenv("google_api_key"))
</code>
</pre>


# 5.**Run the application:** <br/>
python app.py

 # 6.**Access the app** 
To start Streamlit web browser, use the following command:
<pre>
<code id="start-streamlit">
streamlit run app.py
</code>
</pre>
You can view your web browser at (http://localhost:5000) (or http://127.0.0.1:5000) or at a recommended browser link in the comman prompt console. <br/>
Register your desired meal picture and a prompt about it start receiving personalized meal plans and tracking your nutrition.

# **Contributing** 
We welcome contributions to enhance the AI Nutrition App. Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request. Make sure to follow our coding guidelines and include appropriate tests.

# **Contributing Guidelines**
Fork the repository.Create a new branch.
<pre>
<code id="Fork the repository">
git checkout -b feature-branch
</code>
</pre>

**Make your changes.**
**Commit your changes.**
<pre>
<code id="Commit the changes">
git commit -am 'Add new feature'
</code>
</pre>

**Push to the branch** 
<pre>
<code id="Push to origin">
git push origin feature-branch
</code>
</pre>

**Create a new Pull Request.**

# **License**
Apache License <br/>
Version 2.0, January 2004

# **Acknowledgements**
We would like to thank all contributors and the open-source community for their valuable inputs and support.
