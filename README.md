# Llama 2 Chatbot

This is a chatbot app built using the Llama 2 open-source LLM model from Meta. It uses the Llama2-7B model deployed by the Andreessen Horowitz (a16z) team and hosted on the Replicate platform. This app was refactored from a16z's implementation of their LLaMA2 Chatbot to be light-weight for deployment to the Streamlit Community Cloud.

You can try the bot here - [LLAMA2 Chatbot] https://llama2app-dq6xbwry2tf2cw7mnrhsem.streamlit.app/

## Getting Started

### Prerequisites

To use this app, you'll need to get your own Replicate API token. After signing up to Replicate, you can access your API token from their website. You can also try out other Llama 2 models, such as Llama2-13B and Llama2-70B. For more information, please refer to this [Streamlit blog post](https://blog.streamlit.io/how-to-build-a-llama-2-chatbot/#1-get-a-replicate-api-token).

### Installation

1. Clone this repository
```
git clone https://github.com/wolfsbane9513/Llama2_streamlit.git
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the app
```
streamlit run app.py
```

## Usage

Enter your Replicate API token and a message prompt in the chat box to start chatting with the Llama 2 chatbot.

### Bot

![image](https://github.com/wolfsbane9513/Llama2_streamlit/assets/11406551/5bc340c9-03a6-464e-9c7b-94d0ff84d08f)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References

- [Streamlit blog post: How to build a Llama 2 chatbot](https://blog.streamlit.io/how-to-build-a-llama-2-chatbot/#1-get-a-replicate-api-token)
- [dataprofessor/llama2 repository on GitHub](https://github.com/dataprofessor/llama2)
```
