# <a href='https://youtu.be/ceSF_0lUD6c'> Demo Video </a>: This clickable link will redirect to YouTube.


# AI_Agent from scratch 

There are 3 parts to an AI Agent:
- Agent (The one that co-ordinates with LLM and tools)
- LLM (Large Language Model with some limitations like ChatGPT 3.5 has been trained till 2022 data at this point)
- Tools (A way to outsource the information/data to try and overcome the limitation)

The agent I built is Agent Otaku:
- LLM is OpenAI's ChatGPT 3.5
- Tool is this <a href='https://kitsu.io/explore/anime'> Anime Website </a>

Perks are getting to know facts and updates about the latest animes from ChatGPT 3.5 (the free version)


# Langchain Agents Demonstrations

1) SerpAPI Agent
- This API can help search all over the internet, for this particular example, we're making it search using Google Search Engine.
- Learnings: ChatGPT 4 is well-versed and can keep up with the ongoing trends because of internet accessibility. (but this comes with a small price)
- On the other hand, we can combine SerpAPI (tool) with ChatGPT 3.5 (LLM) with an intermediate and still get some results for free.
  
2) Wolfram Agent
- This API helps fetch scientific, mathematical, or cultural data.
- One key finding was we had to give pinpoint questions. Example 'How many hearts does an Octopus have?' and not 'Octopus heart Mystery'. Cause asking vague questions might result in just going in a loop and exhausting the iteration limit. 
3) Youtube Video Summarization
- This agent fetches the transcripts of a particular YouTube video through its API and then summarizes it with the help of an LLM. 
