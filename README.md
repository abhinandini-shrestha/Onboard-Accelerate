🚀 Overview

This project implements an AI-driven onboarding pipeline that converts messy role and team information into a structured Role Profile, generates a step-by-step Onboarding Plan, and compiles a full set of Learning Assets.

The system uses a sequence of LLM-powered agents (Gemini 2.5 Flash-Lite via Google ADK) to deliver:

Clear, role-specific onboarding plans

Automated extraction of expectations, tech stacks, and systems

Structured documentation to help trainers onboard new hires consistently

A notebook-friendly workflow for running multi-agent pipelines asynchronously

🧩 Features
✔️ Multi-Agent Architecture

Built with Google ADK:

Role Context Agent — extracts role_title, team_name, tech_stack, key_systems, expectations

Onboarding Planner Agent — produces a structured onboarding plan with milestones

Learning Asset Agent — creates tasks, readings, codebase explorations, quizzes, and scenario-based exercises

Pipeline Runner — orchestrates all agents and returns a full training bundle

🧠 Technologies Used

Gemini 2.5 Flash-Lite (via Google ADK)

SequentialAgent and InMemoryRunner

Python 3.10+

Jupyter/Kaggle notebooks

Async/await execution for notebook compatibility

📚References

ADK Documentation
https://ai.google.dev/gemini-api/docs/adk/overview

ADK Tools Documentation
https://ai.google.dev/gemini-api/docs/adk/tools

Google.org Supports CodePath to Train 25,000 AI-Native Software Engineers in the Next Two Years. (2024). PR Newswire US.
https://www.prnewswire.com/news-releases/googleorg-supports-codepath-to-train-25-000-ai-native-software-engineers-in-the-next-two-years-302096772.html

Walch, B. (2025). Strategic Onboarding: How to Set Up New Hires for Long-Term Success. Alaska Business Monthly, 41(9), 70–72.
https://www.akbizmag.com/economy/strategic-onboarding-how-to-set-up-new-hires-for-long-term-success/
