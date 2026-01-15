# Chatbot

We are all familiar with ChatGPT and other Chatbots. In this section we will look at how you can create a chatbot that will enable you to have a conversation with your loved one.

This will be done TEXT<->TEXT.

The principle of Retrieaval Augemented Generation (RAG) will be used to get the right chunk of information from the Knowledge Base.

As a user you need not understand this. It is done by AI behind the scenes.

!!! tip "Technical Details"
    Search is done in a number of ways, with the traditional serach by text on the database.

    MySQL also had a vector field where we can embed the post title and content as well as the metadata of the category.

    Siteground does not support this for MySQL but we can create a vector field in a JSON/BLOB field and do cosine similarity search.

    When a user asks a question we can combine WP standard search along with semantic search and pick the top two in each as the content needed to augment the generation.

<br>