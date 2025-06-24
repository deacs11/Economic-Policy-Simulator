# Economic-Policy-Simulator with Autogen
Simulate a Ministry of Economy with AI agents representing key economic ideologies (Keynesian, Monetarist, Labor, Business). Agents debate crisis responses and propose realistic economic policies. Includes full transcript and auto-generated summary PDF.


This project simulates a virtual Ministry of Economy using [AutoGen](https://github.com/microsoft/autogen), where multiple AI agents representing diverse economic schools of thought debate and evaluate public policy scenarios.

## 🎯 Objective

To simulate realistic economic decision-making during complex situations (e.g. inflation, recession, debt crisis) through multi-agent collaboration. Each agent presents policy proposals based on its economic doctrine.

## 🧑‍🤝‍🧑 Agents

- **Keynesian Minister of Economy** – advocates public spending, employment stimulation, and demand-side interventions.
- **Monetarist Central Bank Governor** – focused on monetary supply, inflation targeting, and interest rate control.
- **Entrepreneurs' Spokesperson** – defends market liberalization, tax cuts, and business-friendly measures.
- **Union Leader** – promotes workers' protection, wage growth, and redistribution.
- **Independent Economic Office** – provides neutral statistical and macroeconomic insight.

## 🧠 How It Works

1. **User gives a scenario** (e.g. rising inflation and stagnant growth).
2. **Each agent argues** for a policy response based on their paradigm.
3. A **GroupChatManager** facilitates structured discussion.
4. A **Synthesizer Agent** produces a clear summary of proposals and points of divergence.
5. The entire conversation and its synthesis are saved to a PDF.

## 🔧 Requirements

Install dependencies via pip:

```bash
pip install pyautogen openai python-dotenv fpdf2

