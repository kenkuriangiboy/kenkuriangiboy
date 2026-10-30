# Hi, I'm Ken 👋

I build **automation and AI workflows** that run real businesses. Most of my work so far runs a 17-room hotel in Kerala, India, which I operate remotely from Paris.

- 🤖 **Automation & AI:** n8n (self-hosted), AI agents (Gemini, DeepSeek), RAG & vector search, LLM evaluation, webhooks, REST APIs
- 💬 **Messaging & payments:** WhatsApp Cloud API, Razorpay
- 📊 **Data:** Python, SQL, Power BI, ETL pipelines
- 🛠️ **Infrastructure:** Docker, DigitalOcean, Caddy (HTTPS), Lovable + Supabase

MSc Big Data, Marketing & Management (Toulouse Business School) · Engineering degree (MBCET) · Based in Paris, authorised to work in France.

## Featured project

### [Hotel Automation](https://github.com/kenkuriangiboy/hotel-automation)

An end-to-end automation stack for a working hotel:

- **OTA email extraction:** an AI agent reads MakeMyTrip, Goibibo and Agoda emails and creates or cancels bookings automatically
- **Guest messaging:** a WhatsApp confirmation, a reminder before arrival and a review request after checkout
- **AI WhatsApp concierge:** answers guests by text or voice note in their own language, from the hotel's FAQ through a RAG knowledge base (Supabase pgvector + Gemini embeddings), remembers the conversation and alerts staff about booking requests; tested with an LLM-as-a-judge evaluation (10/10 hallucination traps passed)
- **Error alerts:** an email the moment any workflow fails
- **Direct booking prototype:** Razorpay checkout with signature-verified webhooks

**Impact:** ~200 online bookings a month imported automatically, ~35–50 staff hours saved a month and ~600 guest messages sent automatically.

<img src="https://raw.githubusercontent.com/kenkuriangiboy/hotel-automation/main/docs/screenshots/whatsapp-concierge-demo.gif" alt="WhatsApp concierge demo" width="260">

## Get in touch

[Portfolio](https://kenkuriangiboy.lovable.app/) · [Case study](https://kenkuriangiboy.lovable.app/case-study/hotel-automation) · [LinkedIn](https://www.linkedin.com/in/ken-kurian-giboy/) · Open to automation, AI operations and data roles in Paris or remote.
