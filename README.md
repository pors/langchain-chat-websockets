### LangChain chat with streaming response over FastAPI websockets

Install and run like:

```
pip install -r requirements.txt # use a virtual env
cp dotenv-example .env # add your secrets to the .env file
uvicorn main:app --reload
```

Or using docker-compose :

### Run with Docker Compose

To run the LangChain chat application using Docker Compose, follow these steps:

1. Make sure you have [Docker](https://www.docker.com/) installed on your machine.

2. Create a file named `.env` file 

3. Open the newly created `.env` file in a text editor and add your OpenAI API key:

   ```dotenv
   OPENAI_API_KEY=your_openai_api_key_here
   ```

   Replace `your_openai_api_key_here` with your actual OpenAI API key.

4. Run the following command to build the Docker image and start the FastAPI application inside a Docker container:

   ```bash
   docker-compose up --build
   ```

5. Access the application at [http://localhost:8000](http://localhost:8000).


Thanks to [@hwchase17](https://github.com/hwchase17) for showing the way in [chat-langchain](https://github.com/hwchase17/chat-langchain/tree/master)
