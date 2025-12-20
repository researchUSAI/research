installation:

Mac:
1. open terminal (command + space, type "terminal")
2. cd to folder: `cd ~/Downloads/research-main`
3. run: `chmod +x start.command`
4. run: `./start.command` (opens UI; keep terminal open)
5. next time: just run `./start.command` from the folder

PC:
1. open the folder where you downloaded the repository
2. double-click `start.bat` (opens UI; keep window open)
3. next time: double-click `start.bat` again

<img width="888" height="198" alt="Screenshot 2025-12-20 at 12 37 45 AM" src="https://github.com/user-attachments/assets/60863b78-ed82-481a-8efb-7f23ef0fe2ac" />

<img width="1143" height="275" alt="Screenshot 2025-12-20 at 12 36 34 AM" src="https://github.com/user-attachments/assets/2c906318-f689-4c75-9f19-3cf88dc444bd" />

/endpoint → type in the endpoint where Ollama is running on your computer with /api/generate added at the end. for example, if your local host is http://localhost:11434/. in the window, type, http://localhost:11434/api/generate. if you're unsure what to do, search 'help me find my local ollama endpoint'.

/model → type in the name of the model you plan to use, exactly as it appears at https://ollama.com/library. select your model from the Ollama window drop down menu. then, type in the Ollama chat to trigger the download. if the model you plan to use is not available in the Ollama drop down, run it from a terminal window. open a new terminal window and run the model's execution line e.g. 'ollama run gpt-oss:20b'. keep the terminal open. Then, navigate to the research window. You are ready to go! Always close the running terminal before changing models.

/release → this exports the current conversation to your browser downloads; you can drag and drop these releases into the research window as references from previous conversations, just make sure to give the model some context when you do. sometimes, if a conversation is too long or the material is too dense, it's better to condense your thoughts and formulate a new idea as a starting point

/recover → this deletes the last dropped file or the last response from the model, whichever came last, it's just a way to undo what happened last - 0: yes, 1: no

/intro → add a prompt prefix

/outro → add a prompt postfix

/polarity → 0: explanatory; full vocabulary 1: concise. direct answer. yes or no, if applicable.

**DISCLAIMER:** prompts are sent to a private render server. these are then returned to your local ollama model. the specific structure isn't disclosed. your data is not stored or logged.
prerequisites: ollama must be downloaded separately. the .command will automatically install python 3.6+ for you on mac

For help learning Ollama, here is the fastest way.

https://youtu.be/UtSSMs6ObqY?si=SZlghpMhHZPMAvP9

**TIP:** I have found that you  can easily change model names from the Ollama Desktop App

<img width="869" height="748" alt="Screenshot 2025-12-20 at 12 44 26 AM" src="https://github.com/user-attachments/assets/f50c9367-4121-4b98-9103-16d4062e8cb0" />



