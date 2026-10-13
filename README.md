
# 1. Ollama

# What I ran
I ran my local Qwen model using Ollama from the command line and sent it a test message.

# What broke or almost broke
During setup, Ollama was running the model on the CPU instead of my my GPU.


# 2. ChromaDB

# What I ran
I created a ChromaDB collection in Python, added documents with vectors and queried the collection for the top 2 closest results

### What broke or almost broke
Nothing broke. I created a separate Python virtual environment and had to make sure I ran the script using that environment.


# 3. Hermes

# What I ran
I connected Hermes to my local Ollama model and tested a terminal tool call.

# What broke or almost broke
Hermes installed, but Windows initially could not find the Hermes command on PATH, so I had to fix the CLI path.



# 4. Telegram

# What I ran
I created a Telegram bot with BotFather, configured it with Hermes, started the gateway and sent a test message to confirm that the bot could reply.

# What broke or almost broke
It didn’t work with Telegram at first because the Python Telegram package was missing, so I had to go back and install it.


