# Getting Started with CrewAI - AI Blog Creator 🤖 

This project shows how to use **CrewAI** to automate blog content creation with the help of AI agents. It runs fully inside a single Jupyter notebook.

---

## 🌟 What is an AI Agent?

An **AI agent** is like a smart assistant that can take instructions and perform tasks using AI models (like chatbots, writers, coders, etc.). Each agent is assigned a role (e.g., Writer, Editor) and performs one part of the job.

---

## 🛠️ What is CrewAI?

[CrewAI](https://docs.crewai.com/) is a Python library that helps you create and manage **multiple AI agents** working together. Think of it as a team of AI workers, each with a job, collaborating to complete a bigger task.

In this project, CrewAI is used to:
1. **Plan** a blog post
2. **Write** the content
3. **Edit** the draft
4. **Convert** it to a nice HTML webpage

---

## 🧪 What This Notebook Does

It demonstrates a basic 4-step workflow:
1. **Planning Agent** creates a blog plan and outline
2. **Writing Agent** writes the blog post using the plan
3. **Editing Agent** improves the text and checks grammar
4. **Web Developer Agent** builds a colorful HTML page with text + images

Images are fetched using **SerpAPI**, and the blog post is saved as `current_webpage.html`.

---

## ▶️ How to Use

1. Install needed libraries:
2. Add your **HuggingFace API key** and **SerpAPI key** inside the notebook.
3. Run each cell step-by-step.
4. View your final HTML blog post in your browser.

---

## 📌 Notes

* This is a simple, beginner-level project meant for learning CrewAI and AI agents.
* You can customize each agent, change the topic, or extend the project with more tasks.

Happy experimenting! 🧠💡
