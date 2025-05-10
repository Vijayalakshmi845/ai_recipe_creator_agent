# ai_recipe_creator_agentHere's a `README.md` file you can use for your GitHub repository containing the AI-based recipe generator script:

---

```markdown
# 🍽️ AI Recipe Generator using Cohere

This project is a simple Python script that generates a recipe based on the ingredients you provide. It uses [Cohere's](https://cohere.com) powerful language model (`command-r-plus`) to create creative, human-like recipes.

---

## 📌 Features

- Takes ingredient input from the user
- Uses Cohere's `chat` API to generate a unique recipe
- Outputs the recipe in a clean format
- Easy to run via the terminal

---

## 🧑‍🍳 Example

```

Enter the ingredients: chicken, garlic, and tomatoes

Recipe:

Here's a simple Chicken Garlic Tomato Stew recipe you can try...

\[AI-generated recipe text]

````

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ai-recipe-generator.git
cd ai-recipe-generator
````

### 2. Install Dependencies

```bash
pip install cohere
```

### 3. Set Up API Key

Replace your API key in the script or use an environment variable:

```python
# Optionally in code
co = cohere.Client('your-api-key')

# Recommended: Use environment variable
import os
co = cohere.Client(os.getenv("COHERE_API_KEY"))
```

You can get your API key from [cohere.com](https://dashboard.cohere.com/api-keys).

### 4. Run the Script

```bash
python recipe_generator.py
```

---

## 🔒 Security Note

**Never upload or share your API key publicly.** Use environment variables or a `.env` file with [python-dotenv](https://pypi.org/project/python-dotenv/) for security in production.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🤖 Powered by

* [Cohere AI](https://cohere.com)

```

---

Let me know if you'd like me to generate a sample `recipe_generator.py` filename reference or help add `.env` support for hiding the API key.
```
