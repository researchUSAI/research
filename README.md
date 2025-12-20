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

/intro → add a prompt prefix. session bound (not persistent), not release bound.

/outro → add a prompt postfix. session bound (not persistent), not release bound.

/polarity → 0: explanatory; full vocabulary 1: concise. direct answer. yes or no, if applicable.

**DISCLAIMER:** prompts are sent to a private render server. these are then returned to your local ollama model. the specific structure isn't disclosed. your data is not stored or logged.
prerequisites: ollama must be downloaded separately. the .command will automatically install python 3.6+ for you on mac

For help learning Ollama, here is the fastest way.

https://youtu.be/UtSSMs6ObqY?si=SZlghpMhHZPMAvP9

**TIP:** I have found that you  can easily change model names from the Ollama Desktop App

<img width="869" height="748" alt="Screenshot 2025-12-20 at 12 44 26 AM" src="https://github.com/user-attachments/assets/f50c9367-4121-4b98-9103-16d4062e8cb0" />

You will still need to set the name of the model you would like to use with the /model command, but the list is a quick reference for proper model name and spelling validation.

**TYPO:**

<img width="1133" height="211" alt="Screenshot 2025-12-20 at 12 49 02 AM" src="https://github.com/user-attachments/assets/dd0c2e5e-9415-4fe1-832e-a656758a91fb" />

**/RECOVERY:**

<img width="1131" height="270" alt="Screenshot 2025-12-20 at 12 49 30 AM" src="https://github.com/user-attachments/assets/8439b116-8683-4d02-8574-83940107a382" />

**/MODEL:**

<img width="1131" height="171" alt="Screenshot 2025-12-20 at 12 49 59 AM" src="https://github.com/user-attachments/assets/def30c0b-9f1a-4d32-b564-d0dda9527489" />

**CORRECTION:**

<img width="1135" height="217" alt="Screenshot 2025-12-20 at 12 50 15 AM" src="https://github.com/user-attachments/assets/19402073-d8ad-40d0-8316-309e0e69230b" />

**SOLVED:**

<img width="1129" height="1007" alt="Screenshot 2025-12-20 at 12 50 43 AM" src="https://github.com/user-attachments/assets/112e8189-be25-4485-98db-23a0de717c7c" />

**POLARITY:1**

<img width="1133" height="189" alt="Screenshot 2025-12-20 at 12 54 56 AM" src="https://github.com/user-attachments/assets/1c1b5330-e3cd-4bc9-98b1-236f1d6b0853" />

<img width="1120" height="330" alt="Screenshot 2025-12-20 at 12 55 33 AM" src="https://github.com/user-attachments/assets/41f61497-0264-4be8-aa50-9a81f8aa22b8" />

**/RELEASE**

<img width="1121" height="249" alt="Screenshot 2025-12-20 at 12 56 10 AM" src="https://github.com/user-attachments/assets/36c4a54e-4b78-4f8b-b204-055ea9b7ddc3" />

<img width="1135" height="1089" alt="Screenshot 2025-12-20 at 12 57 03 AM" src="https://github.com/user-attachments/assets/ff9eb718-5596-4a56-8583-d079cbb32a1e" />

<img width="1125" height="281" alt="Screenshot 2025-12-20 at 12 57 31 AM" src="https://github.com/user-attachments/assets/32af839c-1e19-4c6b-b359-f3469c1a6180" />

**DRAG&DROP:**

Drag and drop the release to re:search 

<img width="1128" height="165" alt="Screenshot 2025-12-20 at 12 59 43 AM" src="https://github.com/user-attachments/assets/297bc781-92ff-47be-8454-753805d551a0" />

**/ENDPOINT:**

<img width="662" height="16" alt="Screenshot 2025-12-20 at 12 59 43 AM" src="https://github.com/user-attachments/assets/8fdaae12-dafb-409a-88ed-ad8b6922781c" />

The Ollama default endpoint is already set. If yours happens to be different, you will have to search for it independently. However, any search engine will help you solve the problem of locating it with minor grievances. I hope you enjoy, and best of luck with your re:search! 
