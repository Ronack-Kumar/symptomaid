# SymptomAid

Describe your symptoms, get an AI assessment with urgency level and advice. Supports English and Tamil.

Live: https://symptomaid.vercel.app

---

## What it does

You type out your symptoms in as much detail as you want, hit check, and it returns an urgency level and AI-generated advice on what to do next. The Tamil language support makes it more accessible for regional users.

It's a single-page app — no login, no data stored, just describe and get a response.

> Not a substitute for professional medical advice.

---

## Stack

- HTML, CSS, JavaScript
- Serverless API functions (`/api`)
- Deployed on Vercel

---

## Running locally

```bash
git clone https://github.com/Ronack-Kumar/symptomaid.git
cd symptomaid
```

Open `index.html` directly in a browser for the UI. For the API to work locally you need the Vercel CLI:

```bash
npm install -g vercel
vercel dev
```

Visit http://localhost:3000
