# ResForge AI • Alex

**Autonomous AI Employee for VitalFlow Health**  
*Free resources, grants, pilots, and GTM execution — all handled 24/7.*

## Setup Instructions (Important!)

### 1. Add Environment Variables in Vercel
Go to your Vercel project settings → Environment Variables and add:

- `GROK_API_KEY` = Your real xAI Grok API key
- `SUPABASE_URL` = Your Supabase project URL
- `SUPABASE_ANON_KEY` = Your Supabase anon/public key

### 2. How to Get Keys
- **Grok API Key**: https://console.x.ai/
- **Supabase** (Free tier): https://supabase.com → New Project → Settings → API

The app will automatically switch from demo mode to real mode when these are set.

## Deployment
This repo is connected to Vercel. Every push to `main` triggers automatic deployment.

## Features
- Real Grok-powered AI assistant
- Supabase persistence for claimed resources and grant tracking
- Security hardened (CSP, input sanitization)
- HIPAA notice included

Built for Michael @ VitalFlow Health (Melissa, TX)  
May 2026