# Labs: Beginning AI with open-source tools

## Low-bandwidth setup (do this once, on good internet)
Download these, then copy them to a USB stick for the room:
- The Ollama installer for Windows, Mac, or Linux, from https://ollama.com/download
- The models, by running (after install) `ollama pull qwen2.5:0.5b` and `ollama pull qwen2.5:1.5b`
- Model files are stored in a folder named `.ollama/models` in your home folder. Copy that folder to the USB stick to share models without downloading again.

Model sizes change. Check the size shown on https://ollama.com/library before downloading.

## Lab 1: Install Ollama and run your first model (45 min)
### Windows
1. Open the downloaded file `OllamaSetup.exe` (double-click it).
2. Click **Install**. Wait for it to finish.
3. Click the **Start** button, type `cmd`, and press **Enter**. A black window opens. This is the command prompt.
### Mac
1. Open the downloaded file and drag **Ollama** into **Applications**.
2. Open **Ollama** from Applications. Click **Open** if your Mac asks.
3. Press **Command + Space**, type `Terminal`, press **Enter**.
### Linux
1. Open a terminal.
2. Type `curl -fsSL https://ollama.com/install.sh | sh` and press **Enter**.
### Everyone
4. Type `ollama run qwen2.5:0.5b` and press **Enter**. The first time, it downloads the model.
5. When you see `>>>`, type: `Explain what open source means in two sentences.` Press **Enter**.
6. Ask it a question about your own country. Is the answer right? Write down one thing it got wrong, if any.
7. Type `/bye` and press **Enter** to quit.

## Lab 2: Compare two model sizes (45 min)
1. Type `ollama run qwen2.5:1.5b` and press **Enter**.
2. Ask the same two questions from Lab 1.
3. Compare: Which was faster? Which was more accurate?
4. Type `/bye`. Then type `ollama list` and press **Enter**. Note the size of each model.
5. Discuss with your partner: Which would you put on your office's oldest computer?

## Lab 3 (optional, for Linux or Mac users comfortable with a terminal): llama.cpp
1. Follow the install steps for your system in the official guide: https://github.com/ggml-org/llama.cpp (scroll to "Quick start").
2. Download a small model file ending in `.gguf` from Hugging Face, as your facilitator shows you.
3. Run `llama-cli -m yourmodel.gguf` and press **Enter**.
4. Ask the same question as in Lab 1.

## Lab 4: Ask your own documents (RAG, 60 min)
This version needs no programming. It shows the idea behind RAG: give the model the facts, then ask.
1. Open a text file you have, such as a short policy or procedure (1 page). Or use `sample-policy.txt` from your facilitator.
2. Run `ollama run qwen2.5:1.5b`.
3. Ask a question about the document **without** pasting it. Note the answer (it will likely guess).
4. Now type: `Answer only from this text. If the answer is not in the text, say "I don't know."` Then paste the document text, then your question. Press **Enter**.
5. Compare the two answers. Which can you check?
6. Ask something that is NOT in the document. Did it say "I don't know"?
7. Discuss: A real RAG system does step 4 automatically. It searches your files, picks the best paragraphs, and pastes them in for you.

Facilitators who want a code version can find one under `code/` once it is added (see ROADMAP).
