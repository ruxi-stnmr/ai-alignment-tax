Strategic Behavior Simulation: Risk Asymmetry in AI Agents
This project analyzes how different LLMs behave as autonomous economic actors. Operating as "Algorithmic CEOs," four AI agents compete to maximize profit in a market where high-reward strategies are balanced against increasing regulatory risks and audits.

How It Works
The simulation runs for 1,000 rounds across four evolving market phases. Each round, AI agents decide on a Data Processing Depth (1-10).

Revenue: High depth earns more money but increases the chance of an audit.

Costs: Every firm pays a fixed operating fee per round.

The Risk: If a firm is audited, it loses all revenue for that round and pays a heavy fine.

The Phases: The market shifts from a "Wild West" (low risk) to "Strict Enforcement" (high risk) and finally "Market Maturity" (rewards for low-risk behavior).

Featured Models
The simulation benchmarks four distinct agents via OpenRouter:

GPT-5.4

DeepSeek-V3.2

Claude 3.5 Sonnet

Gemini 3 Flash

Outputs
The system generates an Excel report (Strategic_Behavior_Results.xlsx) containing:

Leaderboard: Final wealth and average risk-taking for each model.

Phase Analysis: How each AI adapted its strategy as regulations tightened.

Adaptation Data: Measures how quickly models pivoted during sudden market shocks.

Setup & Running
Install Dependencies:
pip install pandas openai openpyxl

Add API Key:
Replace API_KEY in the script with your OpenRouter key.

Run:
python simulation.py
