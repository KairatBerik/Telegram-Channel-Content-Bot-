# Telegram Channel Content Bot 
This ChatBot process every post of any telegram channel that exists in TGstat website and will answer your questions based on the posts content.

P.S. It can be wrong




Created and designed by [Kairat Berik](https://www.linkedin.com/in/kairat-berik/).

## 1. Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/KairatBerik/Telegram-Channel-Content-Bot
   ```

2. Install the required Python packages:
   ```sh
   pip install -r requirements.txt
   ```

   **or**

Install these packages yourself: 
 ```sh
  pip install llama_cpp_python
  pip install streamlit
  pip install selenium
  pip install pandas
  pip install langchain_community
  pip install langchain
  pip install huggingface-hub
  ```

3. Install the ChromeDriver that works for you and put the path to it in the code of the app.py
   ```sh
   path = '**here**'
   ```
5. Install any model that you like from HuggingFace portal that **Generates text** and is **gguf**, then also put the path to it in the code of the app.py
   ```sh
   llm = LlamaCpp(model_path='**here**', ........)
   ```
## 2. Usage

1. On the sidebar you can see the **Pick your Telegram Channel**, where you can:
   
      - Search for the Telegram Channel in TGSTAT.com
      - Copy the Link and input the link in the search bar
      - Choose a number of posts you want to grasp(recency). It takes only 20 posts from the start, so by choosing '1' you choosing to take 20 more posts to overall grasp 40 posts, by choosing '2' you choosing to take 20 more posts to overall grasp 60 posts, and so on. 
        
3. On the main side of the page you will see the **Chat with the Bot** showing off the text_input area for you to ask a question and the history of your chat with the Bot.

 P.S. The sidebar is foldable.
 

## 3. Technologies used

- Python
- Streamlit
- Selenium
- Chromedriver
- LangChain
- Any model from HuggingFace portal that Generates text and is gguf


## Author 

Industrial Engineering student at UIC | 4th year | [Kairat Berik](https://www.linkedin.com/in/kairat-berik/).

## License

This project is licensed under the [MIT License](LICENSE).
