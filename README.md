# llm-parliament

LLMs as actors in parliamentary procedure.

This project explores how multiple language models with different roles can work together in a structured debate. Agents are organized into a tree rooted at a chair agent that coordinates several factions. Each faction may have a head agent and additional agents underneath it.

## Agent Tree
- **Chair**: Presents the master prompt and orchestrates the debate.
- **Factions**: Groups of agents representing different agendas. Each faction has a head agent and optional subordinate reasoners.

## Rules of Parliament
1. Chair presents master prompt
2. Factions stand up and offer opening statements
3. Round-robin presentation and criticism of proposals
4. Chair presents final answer

The goal is to combine the perspectives of multiple agents to craft the best possible response to the master prompt.
