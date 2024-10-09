![Architecture](https://github.com/FaisalxWattoo/GenAI-Cold-Email-Generator/blob/main/images/architecture.png)
... 
# Cold Email Generator for Service Companies
====================================================

## Overview
This application utilizes Groq, LangChain, and Streamlit to enable users to input a URL from a company's careers page. It automatically extracts job listings and generates personalized cold emails that incorporate relevant portfolio links. These emails are tailored to specific job descriptions pulled from a vector database.

## Initial Setup
---------------

### Obtain an API Key
Secure an API Key: First, register and obtain an API key necessary for backend services from Groq API Console.

### Configure Environment Variable
```plaintext
Navigate to `app/.env` in your project directory and update the `GROQ_API_KEY` with the key you obtained.
```

### Install Required Libraries
Ensure your environment is prepared by installing the necessary dependencies:
```bash
pip install -r requirements.txt
```

### Launch the Application
Activate the Streamlit application using:
```bash
streamlit run app/main.py
```

## Licensing and Usage
----------------------

### License
This tool is distributed under the MIT License, which permits modification and redistribution.

### Commercial Use
Explicit prior written permission from the author is required for any commercial use of this software. Attribution must be maintained in all copies or significant portions of the software.
![Architecture](https://github.com/FaisalxWattoo/GenAI-Cold-Email-Generator/blob/main/images/email.png)
