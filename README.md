# Assignment
### Conversation History Management and Information Extraction
This project implements two separate tasks:

##### Conversation History Management with Summarization
JSON Schema Classification & Information Extraction
Features
##### Task 1: Conversation History Management
Maintains a running conversation history of user-assistant chats
Implements summarization to keep conversation history concise
Customizable truncation options:
Limit by number of conversation turns (last n messages)
Limit by character length
Periodic summarization after every k-th conversation run
Demonstration with multiple conversation samples and settings

##### Task 2: Information Extraction
Creates a JSON schema to extract 5 user details (name, email, phone, location, age)
Uses OpenAI function calling with Groq API for structured outputs
Validates extracted information against the schema
Demonstrates parsing of 3 sample chats with validation results
