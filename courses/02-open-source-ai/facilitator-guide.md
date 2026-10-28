# Facilitator guide: Beginning AI with open-source tools

## The week before
- Test every lab on the slowest laptop you expect to see.
- Prepare the USB sticks (see "Low-bandwidth setup" in labs.md). Do not count on 20 people downloading models on venue Wi-Fi.
- Send a setup sheet asking people to install Ollama before the day, if they can.
- Write a one-page `sample-policy.txt` for Lab 4, using a local, non-private topic.

## Key messages
- Small local models make mistakes. The goal is to learn how to check them, not to trust them.
- "Open weights" is not always "open source." Read each model's license before using it at work.
- Keep private and government data on machines you control.

## Common problems
| Problem | Fix |
|---------|-----|
| `ollama` command not found | Close and reopen the terminal. On Windows, restart. |
| Very slow answers | Use the 0.5b model. Close other programs. |
| Out of memory | Use a smaller model. |
| Antivirus blocks install | Ask the venue's IT person in advance. |

## Teaching it next
Labs 1 and 2 work well as a 90-minute lunch-and-learn for co-workers.
