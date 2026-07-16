Steps to do

1. Create a PRD
2. Create a FE in stitch
3. Finalize what features I want
4. just talk to a gemini API key
5. Setup a simple ass graph and query through it and talk to it


1st iteration: (DONE)
- Turn 1 notebook into a couple of chunks
- Save those chunks into a pandas DF
- Pass those chunks into an LLM and ask it about the chunks



2nd Iteration: (DONE)
- Turn those chunks from the DF from just text to vector embeddigns with SBERT (locally)
- Have RAG working locally

3rd iteration:
- Now make it handle multiple documents [x]
- Setup an agent whos whole job is to give me a response (instead of just an LLM call) 
- Have it ignore and pre-process blank cells

4: 
- Setup a vector DB like Pinecone for it to work with

5:
- Set up a knowledge graph like Neo4j
- Find relationships in the chunks
- Be able to query the knowledge graph (use whatever NLP I want ig)

6:
- have it use S or some sort of API
- Have multiple agents that focus on specific fields within my knowledge graph that I can talk to


Final Iteration:
- It should have a front end that asks "which topic are you studying today". I then can point it to one of my repos (Classes, Research, etc.)
- When I open that topic, I see a knowledge graph of all the notebooks and PDF's that I have saved on that topic in that specific directory.
- I can ask a question about that topic, and it queries the knowledge graph and tells me an answer. it uses multiple agents, one of them is a writer agent that handles the output, and another 2 agents that focus on code and another on text
- give it memory of past conversations?
