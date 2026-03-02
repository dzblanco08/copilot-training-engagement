# copilot-training-engagement

This repository contains instructions for building a Copilot agent that creates tailored engagement and training activities by analyzing Copilot training session transcripts. The agent generates pro tips, practice prompts, and real-world use cases designed for sharing in Microsoft Teams channels to help empower and enable team members.

## M365 Agent Builder Context
These instructions are intended for use with **Microsoft 365 Agent Builder**. They define the agent’s mission, behavior, and output style so the agent can be configured consistently and reused across Copilot training and enablement scenarios.

> **Prerequisite:** Creating and using agents in Agent Builder requires a Microsoft Copilot license.

## Agent Instructions
See [agent-instructions.md](agent-instructions.md) for the Copilot engagement agent mission, guidelines, step-by-step behavior, and example outputs.

## How to Implement the Agent in M365 Agent Builder

Follow the steps below to create this agent using Microsoft 365 Agent Builder:

1. Open **Microsoft 365 Copilot**.
2. Open the navigation panel and select **Create agent**.
3. Open the **Configure** tab.
4. Copy the contents of [`agent-instructions.md`](agent-instructions.md).
5. Paste the instructions into the **Agent instructions** field.
6. Review or adjust the name and description of the agent as needed.
7. Click **Create** to create the agent.

## Test the Agent
After creating the agent:
1. Provide a Copilot training session transcript as input.
2. Confirm the agent generates 3–5 engagement activities.
3. Validate that the outputs are clear, Teams-ready, and aligned to the guidance in the instructions.

If needed, update the instructions and recreate or refine the agent.

## Share the Agent
Once validated:
- Share the agent with anyone who needs access (e.g., trainers, enablement leads, or team owners).
- Use the agent to support ongoing Copilot training, adoption, and engagement efforts.

This repository serves as the source of truth for maintaining and evolving the agent’s behavior over time.
