# Getting Started with AI: Demos

Every tool below runs in a browser tab. Nothing needs to be installed to use them. Send the prompts in each chat one at a time, in order.

## Demo 1: ChatGPT

- Link: <https://chatgpt.com>
- Multi-purpose chat tool, available for free with paid upgrades
- Upload: none

Chat 1 Prompts:

1.  *What is machine learning? Answer in two sentences.*
2.  *I'm a social scientist and I have no coding background. Explain it again using an example from my field.*
3.  *I don't know what to ask next. Suggest five questions I should ask about machine learning.*
4.  *Before you answer question 2 from your list, ask me three questions about what I already know, so you can pitch the answer at my level.*

Chat 2 Prompt (open a new chat): *What do you remember about me?*

Goal: (1) To show that a chat is a conversation: you can iterate on an answer, tailor it to an audience, and have the assistant ask you questions first, all without repeating the topic. (2) To show that memory is shared across chats.

## Demo 2: Claude

- Link: <https://claude.ai>
- Multi-purpose chat tool, available for free with paid upgrades
- Upload: Chat 1, any PDF paper you know well; Chat 2, the Gapminder CSV in [`data/`](data/)

Chat 1 Prompts (PDF):

1.  *Read this paper and summarize it in five bullet points that a high school student could follow.*
2.  *Draw a theory map of this paper as a diagram: the main concepts, and how the authors connect them.*
3.  *Act as a journal reviewer with deep knowledge of European welfare systems. Give me your three most important critiques, under 100 words in total.*

Chat 2 Prompts (CSV):

1.  *Here is a CSV. Describe what is in it, then find the two or three most interesting trends and plot the most striking one.*
2.  *Show me the Python code that made that plot.*
3.  *Explain that code line by line for someone who has never programmed.*

Goal: (1) To show how to work with an uploaded document, and how the audience, format, role, and length limit you ask for change the answer. (2) To show data analysis without writing code: the file is never modified, and you can ask for the code and an explanation of it.

## Demo 3: Gemini

- Link: <https://gemini.google.com> (Berkeley: sign in with CalNet)
- Multi-purpose chat tool built into Google Drive and Gmail; the Pro version is free with CalNet
- Upload: none (uses your own Google Drive; turn on the Google Workspace connection in settings)

Chat 1 Prompt: *Find the [program handbook] in my Google Drive and summarize what it says about [qualifying exams/ advancing to candidacy]. Tell me which file you used.*

Chat 2 Prompt: *Draft an email to [name] with a short rhyming poem about [topic]. Do not send it; show it to me, and then save it in my drafts.*

Goal: (1) To show that an assistant connected to your accounts can search your own files and draft in your email. Berkeley's CalNet-licensed Gemini is approved for up to P3 protected data; personal accounts are not. (2) Show an application to creative work and that Gemini can send emails on your behalf, if you give it permission

## Demo 4: Perplexity

- Link: <https://www.perplexity.ai>
- Specialty tool for web search with linked sources, available for free with paid upgrades
- Upload: none

Chat 1 Prompt: *What are the most recent estimates of global life expectancy, and how have they changed since 2019? Cite sources.*

Goal: To show answers where every claim has a numbered source you can click and check.

## Demo 5: Gemini Notebook (formerly NotebookLM)

- Link: <https://notebooklm.google.com>
- Specialty tool that answers only from documents you upload, with citations; free
- Upload: Notebook 1, the [Beginner's Guide to Spanish (PDF)](https://srpubliclibrary.org/wp-content/uploads/sites/4/2016/08/Beginners-Guide-to-Spanish.pdf); Notebook 2, 3–5 PDF papers on one topic

Notebook 1 (study materials): in the Studio panel, click **Audio Overview**, **Quiz**, then **Flashcards**. Audio takes a few minutes to generate.

Notebook 1 Prompt: *Make me a one-week study plan from this guide, 15 minutes a day.*

Notebook 2 Prompts (citations):

1.  *What do these papers agree on, and where do they disagree? Cite each claim.*
2.  *What do these papers say about [a topic they do not cover]?*

Goal: (1) To show how one document becomes audio, a quiz, and flashcards for studying. (2) To introduce hallucinations (confident answers that are made up) and show how citations guard against them: each citation bubble opens the exact passage in the source, and for prompt 2 NotebookLM should say the papers do not cover the topic instead of inventing an answer.

## More

- Gapminder source data: <https://www.gapminder.org/data/>
- Follow-up D-Lab workshops: <https://dlab.berkeley.edu/training>
