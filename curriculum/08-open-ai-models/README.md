# Module 8: Open AI models: running locally, choosing models, RAG basics

**Level:** Practitioner  
**Time:** about 6 hours  
**Needs:** a laptop or a phone with a browser; some exercises need an internet connection once.

## Learning objectives
By the end you will be able to:
- Choose a model that fits your hardware
- Explain model licenses (open weights vs. open source)
- Build a simple "ask your documents" tool (RAG)

## Lesson outline
1. Model size vs. memory: rough fit for 8 GB and 16 GB laptops
2. Quantization in plain terms: smaller files, a little less accuracy
3. Model licenses: Apache-2.0 and MIT models vs. custom licenses with limits
4. RAG: find the right paragraphs, then ask the model to answer from them
5. Testing answers: build 10 questions with known answers
6. Builds on [course 02](../../courses/02-open-source-ai/)

## Hands-on exercise: Ask your own documents
1. Follow the setup in [courses/02-open-source-ai/labs.md](../../courses/02-open-source-ai/labs.md).
2. Pull a small embedding model: `ollama pull nomic-embed-text`.
3. Put 5 to 10 public documents (policies, manuals) in one folder as text files.
4. Follow the lab steps to index the folder and ask questions.
5. Write 10 questions where you know the answer. Count how many the tool gets right.
6. Try a different model (for example `ollama pull qwen2.5:1.5b`) and count again. Write down which is better on your hardware.

## Quiz
1. What does RAG do?
2. Is every "open" model open source?
3. How do you test a RAG tool?

<details><summary>Answers</summary>

1. Finds relevant text first, then asks the model to answer using that text.
2. No. Some have custom licenses with limits. Read the license.
3. Ask questions with known answers and count correct ones.

</details>

## Free resources
| Resource | License |
|---|---|
| [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1) | Apache-2.0 |
| [Hugging Face Learn (all free courses)](https://huggingface.co/learn) | Mostly Apache-2.0 |
| [Hugging Face Transformers docs](https://huggingface.co/docs/transformers/index) | Apache-2.0 |
| [fast.ai Practical Deep Learning](https://course.fast.ai/) | Free; see site |
| [LlamaIndex docs](https://docs.llamaindex.ai/) | MIT (software) |
| [Ollama model library](https://ollama.com/library) | Varies by model |

Links checked October 2026. If one breaks, please open an issue.
