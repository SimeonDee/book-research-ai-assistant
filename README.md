# book-research-ai-assistant
AI Book Research Assistant. It contains an Agent powered by OpenAI GPT4.1-mini LLM, equiped with openlibrary API tool-calling. It allows users find information about book of interest using openlibrary api as tool-call.

---
`Adedoyin Simeon Adeyemi` | [LinkedIn](https://www.linkedin.com/in/adedoyin-adeyemi-a7827b160/)

---

## Tools Used:

- Jupyter AI
- OpenAI API
- GPT4.1-mini
- aisuite (model agnostic agentic framework by Andrew Ng and Team)
- openlibrary API (provided as a tool to the Agent)
- requests (RESTful API calls/communications)

## Skills
- Prompt Engineering
- Agentic development
- Tool calling
- RESTful API requests

## Steps and Features Implemented:

- Implemented API calls to Open Library API
- Wrapped the API Call in a Tool Function (for AI Agent use)
- Implemented search_books and get_book_details tools, where each tool is a function that makes API request to open Library API (for LLM use)
- Built a Chat Handler with Automatic Function Calling
- Used OpenAI’s gpt-4.1-mini model to generate final response using equiped with the search_books and get_book_details tools and provides summary of the requested information.

## Sample Respons

`Input Query:` 
    Search for books with 'Linear Algebra' in the title and tell me about the one with the most editions

`Response:`
    The book with the most editions that has 'Linear Algebra' in the title is "Bundle" by Jeffrey D. Camm, James J. Cochran, Michael J. Fry, Jeffrey W. Ohlmann, and David Ray Anderson. It has 97 editions. However, there is no specific description available for this book.

    If you want, I can provide details about other notable books on linear algebra with many editions as well.
