# Deal Desk Guardrails 🛡️

A high-performance, professional **GTM Finance Engine** built with Next.js 15. This platform enables Deal Desk and Finance teams to evaluate enterprise deal profitability and margin protection in real-time.

## 🚀 Key Features

- **Automated Profitability Analysis**: Instant calculation of Base ARR, AI ARR, and Gross/Net margins based on granular inputs (seats, usage units, discounts).
- **AI Executive Brief**: One-click deal summaries using OpenAI (GPT-4o-mini) with a deterministic fallback for executive decision-making.
- **Smart Guardrails**: Real-time evaluation against finance policies (Approvals, Rejections, Conditional terms).
- **Strategic Advisory**: Built-in logic to suggest deal terms and risk mitigation strategies.
- **Elite Aesthetic**: High-contrast, typography-focused "Finance Terminal" UI with support for Dark/Light modes.

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **AI**: OpenAI API
- **Deployment**: Vercel

## 💼 Business Logic

The engine follows standard enterprise SaaS pricing models:
- **Base Subscription**: $Seats \times Price/Seat/Month \times 12$
- **AI Packages**: $Units \times Price/Unit \times 12$
- **Partner Logic**: Net margin calculations account for channel incentives and partner take-rates.

---
Built for high-velocity GTM organizations.
