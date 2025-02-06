

Ininitalize project with `poetry`:
```sh
poetry init
```

Install dependencies:
```sh
poetry add python-dotenv black isort langchain langchain-openai langgraph
```

To check if the `.env` is being imported, evaluate the following expression:
```python
import os
...
os.environ['OPENAI_API_KEY']
```