# Peter (Summary): Slack-Native AI Assistant with RAG Capabilities

This case study summarizes "Peter," an internal AI assistant I helped develop during my internship at StatStak. Peter is a Slack-native tool that uses Retrieval-Augmented Generation (RAG) to help team members query meeting transcripts and link action items to product tickets.

## 🧠 Problem

Our team had thousands of hours of meeting transcripts across accounts and needed a way to:
- Answer questions about past decisions and discussions
- Link follow-ups to Notion tickets and Slack threads
- Automatically find context across accounts and client needs

## 🧰 My Role

- Took over the existing codebase and deployed updates via Railway
- Fixed Slack thread retention bugs to maintain message context
- Integrated Pinecone vector DB for transcript retrieval
- Connected the assistant to Notion for ticket linking
- Engineered prompts, message parsing, and Slack threading logic

## 🔧 Tech Stack

- OpenAI (GPT-4)
- Pinecone (vector database for RAG)
- LangChain
- Slack API
- Notion API
- Railway (deployment platform)
- GitHub (private repo)

## 🧪 Example Query (Anonymized)

> **User:** "Did we already discuss pricing tiers for [client]?"  
> **Peter:** "Yes — discussed on May 14th. Summary: offering 3-tier model based on usage. View: [Notion ticket link]"

## 🔒 Note

This is a high-level, anonymized summary of a proprietary internal tool. The full implementation remains private to protect company IP.

---

📬 Interested in more details? I’m happy to walk you through it in an interview.
