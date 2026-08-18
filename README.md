<<<<<<< HEAD
# LangChain Learning Hub

A single, organized collection of CampusX's LangChain repos, merged for personal study.
Original source: [campusx-official](https://github.com/campusx-official) on GitHub.

## Suggested Learning Order

| # | Topic | Folder | What's Inside |
|---|-------|--------|----------------|
| 1 | Models | [`langchain-models/`](./langchain-models) | LLMs, Chat Models, Embedding Models |
| 2 | Prompts | [`langchain-prompts/`](./langchain-prompts) | Prompt templates, chat prompt templates, message placeholders, chatbot demo |
| 3 | Structured Output | [`langchain-structured-output/`](./langchain-structured-output) | TypedDict, Pydantic, JSON schema-based structured output |
| 4 | Output Parsers | [`langchain-output-parsers/`](./langchain-output-parsers) | StrOutputParser, JsonOutputParser, PydanticOutputParser, StructuredOutputParser |
| 5 | Runnables | [`langchain-runnables/`](./langchain-runnables) | RunnableSequence, RunnableParallel, RunnableBranch, RunnableLambda, RunnablePassthrough |
| 6 | Chains | [`langchain-chains/`](./langchain-chains) | Simple, sequential, parallel, and conditional chains |
| 7 | Document Loaders | [`langchain-document-loaders/`](./langchain-document-loaders) | Text, PDF, CSV, Directory, WebBase loaders |
| 8 | Text Splitters | [`langchain-text-splitters/`](./langchain-text-splitters) | Length-based, structure-based, markdown, Python code, and semantic-meaning-based splitting |
| — | Notebooks | [`notebooks/`](./notebooks) | Colab notebooks (RAG, vector stores, retrievers, etc.) |

## Notes

- Each folder retains its original repo's file structure; nothing was rewritten, only reorganized.
- `notebooks/` holds supplementary Colab `.ipynb` files that go deeper into specific topics (RAG, retrievers, vector stores) not covered by the standalone repos above.
- Original repo licenses/attributions belong to CampusX; this is a personal study aggregation, not a redistribution for other purposes.

## Setup

Most folders include or rely on a shared set of dependencies. A good starting point:

```bash
pip install langchain langchain-openai langchain-community langchain-experimental python-dotenv
```

Check individual folders for any `requirements.txt` (e.g. `langchain-models/requirements.txt`) for extra dependencies.
=======
# Langchain
>>>>>>> 6a321e0416252de54c439853ca2b89fdcac9d64f
