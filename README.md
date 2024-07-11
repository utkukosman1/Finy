# This project housing 2 different basic-level LLM bots with different LLM models. I used LangChain framework on Python for creating RAG chains.

1-) GPT4-ALL mistralai/Mistral-7B-Instruct-v0.1 architecture
-Supported with PDF formatted data about portfolio optimization in Turkish.
-Runs locally on terminal
-Used a Huggingface embedding model "sentence-transformers/distiluse-base-multilingual-cased-v2".

My experinces:
-If you want to create a real application which users can use, I don't suggest running LLM's on your local machine, use API's instead. It needs to use a lot of computing power and it's a little bit hard to develop because of the under-developed libraries which is not easy to use and accessible. It can be really overwhelming for junior devolopers like me.
-I think the embedding model I chose is really usable, espicially if you are working on multilingual tasks.

2-) OpenAI gpt-3.5-turbo-instruct-0125 architecture
-Supported with an web-page about HSBC giving stock advises, which will be developed with an external data connection via Tavily Search Engine API or Google.
-Uses OpenAI embeddings ("text-embedding-ada-002").
-Created with free OpenAI credits.

My experinces:
-OpenAI API is really smooth to use, it works perfectly with LangChain in my opinion.
-It gives better results and outputs than the GPT4ALL model above.
-More fast for usecases because of good API connetcions, don't have to download same embedding model over over if you forget to save it :) .
-More easy to create a invoke chain.
-GPT models understanding for prompt templates are better than the others I guess, I can't talk about Gemini because I never worked with it, yet.


Don't forget these are my experinces with a really basic demo of an AI assistant. You could or would have different experinces and if you do, please share with me via here.

I hope this repo helps for having a general understanding RAG and using different LLM's and running them differently.
