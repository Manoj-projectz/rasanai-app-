# rasanai-app-
AI-powered recipe &amp; meal planning app for Indian home cooks — import from Instagram/YouTube, plan your week, and order missing ingredients via Swiggy Instamart. Built with React Native + Expo + GPT-4o.
# 🍳 RasanAi — Your AI Rasoi Companion

> Discover · Plan · Cook · Order — all in one app, built for Indian home cooks.

---

## What is RasanAi?

RasanAi is an AI-powered recipe and meal planning app that fits into the way Indian home cooks already think about food. Paste an Instagram Reel or YouTube Short — RasanAi extracts the recipe, translates it, and adds it to your personal collection. Plan your week's meals, then order every missing ingredient directly through Swiggy Instamart — without leaving the app.

## Key Features

| Feature | Description |
|---|---|
| 📥 **Recipe Import** | Paste any Instagram Reel, YouTube Short, or URL — AI extracts ingredients & steps |
| 🗓️ **Meal Planner** | Weekly plan with smart validations, auto-fill, and past-slot protection |
| 🛒 **Grocery Basket** | Ingredients auto-added from recipes, grouped by dish |
| 🛵 **Swiggy Instamart** | One tap → ingredients matched & added to your Instamart cart |
| 🤖 **AI Assistant** | Ask RasanAi anything — substitutions, nutrition, voice commands in EN / हि / த |
| 🎙️ **Hands-free Mode** | Cook step-by-step with voice guidance |
| 🌐 **3 Languages** | English, हिन्दी, தமிழ் throughout the app |

## Swiggy Instamart Integration

RasanAi integrates with **Swiggy Instamart via MCP** to close the loop between planning and ordering:
User adds recipe → marks missing ingredients → taps "Order via Instamart"
↓
RasanAi backend searches Instamart catalogue for each ingredient
↓
User reviews matched products, swaps alternatives if needed
↓
Cart auto-filled in Swiggy → user completes checkout in Swiggy app

**Stack:**
- Mobile: React Native (Expo SDK 54) — TypeScript
- Backend: Node.js / Express — MCP client for Swiggy APIs
- AI: OpenAI GPT-4o-mini (chat) + Whisper-1 (voice)
- Auth: OAuth 2.1 PKCE via expo-web-browser
## Tech Stack
Mobile → React Native + Expo SDK 54 (TypeScript)
Backend → Node.js + Express
AI / NLP → OpenAI GPT-4o-mini + Whisper-1
Grocery Orders → Swiggy Instamart MCP
Storage → AsyncStorage (local) + Express sessions

## App Screens
| Screen | Purpose |
|---|---|
| Home | Personalised feed, category filters, trending recipes |
| Recipe Detail | Ingredients, steps, hands-free cooking mode |
| Meal Planner | 7-day weekly plan with smart slot validations |
| Grocery Basket | Cart with per-recipe grouping |
| Instamart Order | Ingredient matching + Swiggy cart auto-fill |
| AI Assistant | Voice + text chat with recipe-aware context |
| My Recipes | Personal collection of imported recipes |
## Status
> 🚧 Currently in private beta. Swiggy Instamart MCP integration pending Builders Club approval.
## Contact
Built by **Manoj deebak**
📧 tektees@gmail.com
<img width="591" height="1280" alt="WhatsApp Image 2026-05-31 at 6 09 07 PM" src="https://github.com/user-attachments/assets/f8ee5201-b151-4fa6-be85-4f9f4aff50e8" />
<img width="739" height="1600" alt="WhatsApp Image 2026-05-31 at 6 09 40 PM" src="https://github.com/user-attachments/assets/134d40cf-0393-482a-a6ee-0f9946d93b71" />

