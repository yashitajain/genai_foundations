**Created a simple openAI API call to understand more about prompts, parameters and role.**

**Prompts:** 

- **What works?**- Asking for specifics helps narrow the search. For eg: "What is the top travel credit card based on US and on latest updates? Give concise answer"

- **What fails?** - Asking very vague and not specific to your personal choices? For eg: "What is the top 1 travel credit card?"

**Role:**

- **Developer Role** - Makes the response more reasoning and give explanation  "role":"developer",
            "content": "Talk like a credit card expert"},
            
- **User Role** - Takes in user request

**Parameters:**

- **Model** - making sure to not use higher models that can increase costs

- **Reasoning** - this one was pretty important. When set to *reasoning = {"effort":"low"}*, it took half the time with hardly affecting the answer's quality 

- **Instructions** - helps with structuring the output response. For eg: instructions = "Show answer as a table",
