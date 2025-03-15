# Outskill Gen AI Workshop, March 15 2025
- Notes by MD Arshad Khan

__Organizer__: Phani Krishna, Outskill  
__Session 1__: Divij Bajaj, Microsoft

- __Gen AI__ is a type of AI that __creates original content__ - such as test, images, videos - __by learning patterns from large datasets__
- Use cases of AI
    - Digital assistants
        - Eg. Siri
    - Search engines
        - Eg. Google
    - Transportation and Navigation
        - Eg. Google Maps
    - Advertising
        - Ad creation
        - Budget optimization
- Branches in AI
    - AI - Inteligent Machines (Broadly defined)
        - Machine Learning - Pattern Recognition
            - Deep Learning - Neural Networks and learning patterns in unstructured data (images, text, audio)
                - LLMs - Pattern recognition - Learning to understand natural language (text)

- Large Language Models (LLMs)
    - Subset of Gen AI that focuses primarily on text
- How LLMs work
    - __Tokenize__: Break the prompt text into smaller tokens
    - __Embeddings__: Convert the text into numbers. Similar words have closer distance (a word can have different meanings based on the context)
    - __Self attention__: The model focuses on the most important parts of the prompt text
    - __Prediction__: Predict the next word - word-by-word to construct the complete sentence
    - __Response Generation__: Complete the response, maintaining relevance and coherence

## Multiple Prompting Techniques
- Zero Shot Prompting
- Few Shot Prompting
- Chain of thought Prmpting
- Tree of thought prompting
- DiVeRSe Prompting
- ...

## "The Magic Prompt" Formula
- Give context giving details when you prompt.
- For creative writing tasks, ChatGPT 4o is ok-ok. Claude 3.5 is better at it!
- The prompt hould have have
    - __Context__ - info about the setting
    - __Task__ - What to do
    - __Instruction__ - on what to include and take care of in response
    - __Data__ - data to use in response

## Applications of Gen AI
- __Video summarization__
    - YouTube videos are very long
        - Gemini can watch YouTube videos and provide a summary
        - gemini.google.com - provide the YouTube URL and your requirements for summarization in the prompt
            - The summary includes links to video sections with timestamps!
            - You can prompt with follow-up questions that will re-query the video!
- __Image generation__
    - Eg. Generate a photorealistic image of Elon Mush fighting Sam Altman, both bruised, in a cage fight.
    - Paid tools
        - __Midjourney__
        - __DALL-E__ - comes with paid OpenAI subscription
    - Free alternative
        - Grok Image Generation
        - [grok.com](grok.com) (From X)
- __Email reply generation__
    - Gemini feature is built-in to GMail
    - Summarize this email checks the __entire email thread__ and summarizes!
- __Want to discuss with the LLM, something about strategy/marketing plan etc.__
    - I have Rs. 10,000 to invest and 30 days. Give me 3 business models I can use o reap Rs. 1,00,000 from my investment. The works should not be service-based, and involve no coding or low-code tools. Additionally no ads, as I do not have experience in ad management.
        - ChatGPT 4o model is NOT good for this as it does not reason
        - ChatGPT o1 will spend time reasoning, and you can even go through its reasoning. It takes time for this (uses "Chain of thoughts", and reinforcement learning), and produces much more relevant output.
        - chat.deepseek.com - is a reasoning-based alternative
- __Job Hunting using AI__
    - LinkedIn AI feature - convert profile to PDF
    - Upload the PDF (resume) in ChatGPT 4o, as context, so it knows about you
    - Now prompt - "As a career adviser, I would like you to re-word the CV I have given you. Please tailor it to the following Job Description (JD) to maximise the chances of getting an interview. Include any keywords mentioned in the job post. Organize the structure, summary , and experience in a method you deem best for the desired outcome. The JD: [[insert JD here]]"
    - Now prompt to modify the output - "I would like you to create a table with 3 columns, highlighting experience gaps, suggested improvements, and their priority rankings for securing the job."
    - No ask th voice feature of ChatGPT 4o to have it behave like an interviewer and ask you interview questions on relevant topics. It will interview and provide feedback both verbal and written.
- You want to ask question on the latest event, but the LLM model has a date cutoff
    - Prompt: Prompt about market research to understand the Indian coffee market, its growth potential, and start a coffee business
    - ChatGPT 4o has "Search the Web" options as well
    - Use __Perplexity__ as it is better at this!

## More tools (mostly paid tools)
- __Writesonic__ - [app.writesonic.com](app.writesonic.com)
    - To generate __SEO-focused content__ for web sites, blog posts etc.
        - Given a topics to genrate the bog post on, it will search through websites (top ranked ones), and create the new post for you. Many parameters can be customized in this process of content writing.
- __Emily AI__ - Add as a Brave/Chrome browser extension
    - You want to chat with the website, or chat with the YouTube video
    - Emily extension can be used to generate comments on LinkedIn posts
- __Supergrow__
    - Convert blog article into a LinkedIn post
    - You can even include a carousel using the Carousel maker feature in Supergrow
    - There is a feature to generate a blog post from a YouTube video!
- __Numerous AI__ - [numerous.ai](numerous.ai)
    - for MS Excel and Google Sheets
    - data in the sheets is __private__!
    - Eg. Google sheets -> Extensions -> Add ons -> Add Numerous AI
    - Generate formula
    - Sentiment analysis and classification
    - Keyword extraction
    - Summarization
- Image (infographics) information retrieval
    - Give an image as input, and get insights form th e image - eg. a dashboard image with many metrics
    - ChatGPT 4o can do this
    - Claude can also do a good job of this.
- In the above example, we can also create a dashboard out of the given image! No need to code!!
    - Right now ChatGPT cannot do this, but Claude can.
- Data analysis using AI
- __Suno__ - Music generation - [suno.com](suno.com)
    - Create a calm lo-fi chill track with smooth beats, mellow piano, and relaxing background sounds. The theme should help people focus and unwind while studying.
- __[rollout.site](rollout.site)__
    - Build stunning websites
    - Eg. Generate a OTT platform like Netflix

## Keeping updated
- [theresanaiforthat.com](theresanaiforthat.com)
    - Search and filter tools based on what kind of task you need help with
