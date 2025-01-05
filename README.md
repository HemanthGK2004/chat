# Next.js AI Chatbot

An **open-source AI chatbot template** built using Next.js and the AI SDK by Vercel.

---

## Features

### Powerful Framework with Next.js
- Built using the Next.js App Router for efficient navigation and improved performance.
- Includes React Server Components (RSCs) and Server Actions for enhanced server-side rendering.

### AI SDK by Vercel
- Unified API for generating text, handling tools, and structuring objects with Large Language Models (LLMs).
- Supports multiple providers, including OpenAI (default), Anthropic, and Cohere.
- Prebuilt hooks to simplify the creation of interactive and generative interfaces.

### Styling and Accessibility
- Styled with **Tailwind CSS** for a modern look and feel.
- Component primitives powered by **Radix UI** for accessibility and flexibility.

### Data Persistence and Storage
- **Vercel Postgres (powered by Neon):** Stores user data and chat history.
- **Vercel Blob:** Efficiently handles file storage needs.

### Secure Authentication
- **NextAuth.js** is integrated for secure and straightforward user authentication.

---

## Supported Model Providers

The template is preconfigured to work with OpenAI's `gpt-4o` by default. However, thanks to the AI SDK, you can easily switch to other providers such as:
- [Anthropic](https://anthropic.com)
- [Cohere](https://cohere.com/)
- [OpenAI](https://openai.com)
- [And more](https://sdk.vercel.ai/providers/ai-sdk-providers)

---

## Deploying Your Chatbot

Deploy your custom chatbot to **Vercel** in just a few clicks:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fai-chatbot&env=AUTH_SECRET,OPENAI_API_KEY&envDescription=Learn%20more%20about%20how%20to%20get%20the%20API%20Keys%20for%20the%20application&envLink=https%3A%2F%2Fgithub.com%2Fvercel%2Fai-chatbot%2Fblob%2Fmain%2F.env.example&demo-title=AI%20Chatbot&demo-description=An%20Open-Source%20AI%20Chatbot%20Template%20Built%20With%20Next.js%20and%20the%20AI%20SDK%20by%20Vercel.&demo-url=https%3A%2F%2Fchat.vercel.ai&stores=[{%22type%22:%22postgres%22},{%22type%22:%22blob%22}])

### Prerequisites:
1. Set up the required environment variables (`AUTH_SECRET` and `OPENAI_API_KEY`).
2. Use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables) to store secrets securely.

---
