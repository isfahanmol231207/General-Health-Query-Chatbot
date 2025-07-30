#  General Health Query Chatbot 
This project demonstrates how to create a simple, safe, and friendly **health-related chatbot** using a **Large Language Model (LLM)** via the Together.ai API. The chatbot answers general health-related questions while avoiding harmful or diagnostic advice using carefully designed prompts.

---

## Objective

Develop a conversational chatbot that:
- Responds to **general health queries**
- Uses **prompt engineering** to provide **friendly and informative** answers
- Applies **safety filters** to avoid giving medical diagnoses or critical health instructions

---

##  Tools and Technologies

-  **LLM Used**: `mistralai/Mistral-7B-Instruct-v0.1` (Free and open-source via [Together.ai](https://together.ai))
- **API Platform**: [Together.ai Chat API](https://api.together.xyz)
-  **Language**: Python (with `requests` for HTTP calls)

---


**User Query:**
What are the symptoms of flu?
**Bot Response:**
Flu, or influenza, is a viral infection that can cause a wide range of symptoms. Some common symptoms of the flu include:

1- Fever or feeling feverish

2- Cough

3- Sore throat

4- Runny or stuffy nose

5- Muscle or body aches

6- Headaches

7- Fatigue

8- Some people may also experience vomiting and diarrhea, although this is more common in children than adults.



## Safety Design
1- The system prompt instructs the model to behave like a helpful but limited assistant, giving only public health info.

2- Dangerous or diagnostic content is filtered at the prompt level to avoid misuse.

3- Intended only for general education, not treatment or emergency use.

