# A Basic RAG App
A Basic RAG App developed following the substack tutorial by [Niharika Batra](https://niharikabatra.substack.com/s/16-week-aiml-series)

[Github Link](https://github.com/niharika2309/basic_RAG/tree/main)

## Step 1 - Chunking
` python step1_extract_and_chunk.py `

## Step 2 - Embedding
`python step2_embed.py`

## Step 3 - Search with reranking
`python step3_search.py "Can I take a day off to attend my sister's wedding?"`


### Without Reranking
`python step3_search.py --no-rerank  "How much vacation do I get after one year?"`

## Step 4 - Generate answer using LLM
`python step4_answer.py "Can I take a day off to attend my sister's wedding?"`

# Run it in the browser
The same four steps, as a familiar chat interface — no terminal needed after the one-time setup:

`streamlit run app.py`

then open http://localhost:8501. Ask a question, get an answer. 
