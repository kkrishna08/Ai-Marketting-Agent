# Ai-Marketting-Agent
LinkedIn Carousel Generator Agent – n8n Workflow

An intelligent automation workflow built in n8n that fetches real-time enterprise storage news, analyzes it using AI, extracts insights, and converts them into LinkedIn carousel content, including slide copy, image prompts, and captions — ready for posting.

🚀 What This Workflow Does

This automation transforms raw RSS feeds into a full LinkedIn carousel asset using LLM intelligence:

🔹 End-to-end Flow

✔ Collects form input (topic, ICP, keywords, etc.)
✔ Fetches top industry news from multiple RSS feeds
✔ Extracts headlines, summaries, links, and metadata
✔ Uses AI to analyze and extract:

Main pain point

ICP description

Big idea / central hook
✔ Automatically generates:

5 slide contents

LinkedIn-style caption

Image prompts (for manual or API-based image generation)
✔ Exports JSON with everything structured and ready to use

✨ Key Features

📰 Real-time news extraction via RSS
🧠 AI-powered insight extraction (pain points, ICP, messaging)
📊 Dynamic 5-slide carousel copy builder
🖼 Image prompt generator (supports manual or Gemini Image API)
💬 LinkedIn caption formatter (with emojis and hooks)
📁 Final output organized in JSON for easy slide and caption use

🔧 Tools & Technologies
Component	Purpose
n8n	Workflow automation
RSS Feeds	Real-time industry content
JavaScript Nodes	Custom data formatting
Google Gemini LLM	Insight extraction & slide creation
Manual Canva Integration	Final slide design using prompts
🛠 Setup Instructions

1️⃣ Import the .json workflow file into n8n
2️⃣ Add Gemini API credentials (or use manual image creation)
3️⃣ Customize RSS sources and keywords
4️⃣ Run the workflow
5️⃣ Use Canva/Figma/DALL·E to generate slides using final prompts

⚠️ Known Limitations

🚫 Image generation is disabled due to API credit limits (manual image creation used instead via Canva).
🤖 AI content requires prompt discipline for JSON compatibility.
🔍 Make sure RSS sources are reliable and active.

🤝 Contributions

Want to improve this agent with auto-publishing to LinkedIn or scheduling support?
Feel free to fork, enhance, and submit PRs!

📄 License

MIT License – Free to use, modify, and improve.

🗂 Project Output Includes:
📌 carousel_slides.json – Final 5-slide content
📌 caption.txt – LinkedIn post caption
📌 prompts.txt – Image prompts for manual Canva/DALL·E rendering
