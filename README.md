# Game-of-thrones-personality-matcher

## Description
This project implements t-SNE on the Game of Thrones dataset, providing a personality matching feature for characters. Users can select a character, and the system recommends the closest-matching character based on their personalities.

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/Game-of-thrones-personality-matcher.git
```
   
2. Navigate to the project directory:
```
cd Game-of-thrones-personality-matcher
```

3. Install dependencies using the following command:
```
pip install -r requirements.txt
```

4. Run the Streamlit app using the following command:
```
streamlit run app.py
```
This will launch the web app, and you can access it in your browser.

(Optional) If you are using these application on an instance/VM in Cloud Platform:
```
streamlit run --server.port 8501 --server.address <your ip address> app.py
# Example: streamlit run --server.port 8501 --server.address 0.0.0.0 app.py
```
Note:
Make sure you have Python installed.
The app uses the Streamlit library, and it will be automatically installed with the requirements.
