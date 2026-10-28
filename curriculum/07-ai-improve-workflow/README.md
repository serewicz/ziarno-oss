# Module 7: Using AI to improve a workflow

**Level:** Practitioner  
**Time:** about 5 hours  
**Needs:** a laptop or a phone with a browser; some exercises need an internet connection once.

## Learning objectives
By the end you will be able to:
- Map a real workflow step by step
- Pick one step where an open model can help
- Run that step with a local model through Ollama
- Measure time and errors before and after
- Keep private data private

## Lesson outline
1. Map the workflow on paper: steps, who, time each step takes
2. Pick a step that is text-heavy, repeated, and low-risk (drafting replies, summarizing, sorting)
3. Run an open model locally so data never leaves the machine
4. Writing prompts: role, task, example, format
5. Measure: time per item and errors per 20 items, before and after
6. A human always checks the output
7. Privacy: no personal data in cloud tools; check local law

## Hands-on exercise: Speed up one step with a local model
1. Write your workflow as numbered steps. Time yourself doing 10 items of the slowest text step. Write down minutes and errors.
2. Install Ollama from https://ollama.com/ (click **Download**, choose your system, run the installer).
3. Open Terminal (Command Prompt on Windows). Type `ollama run llama3.2:1b` and press Enter. Wait for the download (about 1.3 GB; do this on a good connection).
4. At the `>>>` prompt, paste a prompt like: "You are a clerk at a ministry. Summarize this letter in three bullet points and suggest a category: complaint, request, or information. Letter: ..." Paste a letter with names removed.
5. Adjust the prompt until the output is useful. Add one good example to the prompt.
6. Do the same 10 items again with the model's help. Time it and count errors.
7. Write a short note: before minutes, after minutes, errors before, errors after, what a human still has to check.
8. Type `/bye` to exit.

## Quiz
1. Why pick a low-risk step first?
2. What two things should you measure?
3. Why use a local model for office letters?

<details><summary>Answers</summary>

1. Mistakes are cheap and you learn safely.
2. Time and errors.
3. Private data stays on your machine.

</details>

## Free resources
| Resource | License |
|---|---|
| [Ollama](https://ollama.com/) | MIT (software) |
| [Ollama model library](https://ollama.com/library) | Model licenses vary; check each |
| [Ollama API docs](https://github.com/ollama/ollama/blob/main/docs/api.md) | MIT |
| [Open WebUI (browser chat for Ollama)](https://github.com/open-webui/open-webui) | See repo license |
| [Principles for Digital Development](https://digitalprinciples.org/) | CC BY-SA 4.0 |

Links checked October 2026. If one breaks, please open an issue.
