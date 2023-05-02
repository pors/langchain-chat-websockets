### LangChain chat with streaming response over FastAPI websockets

Install and run like:

```
pip install -r requirements.txt # use a virtual env
cp dotenv-example .env # add your secrets to the .env file
uvicorn main:app --reload
```

Thanks to [@hwchase17](https://github.com/hwchase17) for showing the way in [chat-langchain](https://github.com/hwchase17/chat-langchain/tree/master)
