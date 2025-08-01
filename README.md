🎓 AI Task Automator for Students
AI Task Automator is an intelligent, end-to-end academic assistant designed to simplify the life of students. With just a topic input, it autonomously performs web research, extracts meaningful content, summarizes it using OpenAI’s GPT models, and transforms the results into a ready-to-use PowerPoint presentation — complete with a quiz at the end. Whether you're preparing for a class, a presentation, or just need crisp notes, this tool gets it done in minutes.

🧠 How It Works
The workflow starts with a smart search via DuckDuckGo, fetching topic-relevant content while preserving safety and privacy. The scraped text is then passed to GPT-3.5/4 for summarization, structured into key points or markdown, and finally converted into slides using python-pptx. Optionally, the system can auto-generate quiz questions to test comprehension — a unique learning booster built right in.

🏗️ Project Architecture
The entire workflow is implemented in a single, interactive Jupyter Notebook (.ipynb) — making it simple to follow, modify, and deploy. Each step of the pipeline (searching, summarizing, slide generation, and quiz creation) is contained within clearly labeled cells for seamless execution. This notebook-first design is perfect for students and educators who want results fast without setting up complex environments.

🛠️ Tech Stack
🔍 Web Search: duckduckgo_search

🤖 LLM Integration: OpenAI API (GPT-3.5/4o mini)

📊 Presentation: python-pptx

💻 UI Layer (optional): Gradio 

📦 Environment: Python 3.10+, .env config, runs in Colab or VSCode
