---
title: "When Is Enough Not Enough? Illusory Completion in Search Agents"
collection: publications
category: conferences
permalink: /publication/2026-colmw-illusorycompletion
excerpt: 'Search agents often conclude a task is complete while a constraint remains unverified; we diagnose this illusory completion along agent trajectories with the Epistemic Ledger.'
date: 2026-08-01
venue: 'COLM 2026 Workshop'
paperurl: 'https://arxiv.org/abs/2602.07549'
citation: 'Dayoon Ko, Jihyuk Kim, Sohyeon Kim, Haeju Park, Dahyun Lee, Gunhee Kim, Moontae Lee, Kyungjae Lee. (2026). &quot;When Is Enough Not Enough? Illusory Completion in Search Agents.&quot; <i>COLM 2026 Workshop</i>.'
authors: '<strong>Dayoon Ko</strong>, Jihyuk Kim, Sohyeon Kim, Haeju Park, Dahyun Lee, Gunhee Kim, Moontae Lee, Kyungjae Lee'
---

Search agents increasingly answer complex questions that place several constraints on the answer, but a correct final answer does not show whether the agent found evidence for each one. We identify *illusory completion*, where an agent concludes the task is complete while a constraint remains unverified: it occurs in at least 74% of agents' wrong answers and even in 16–48% of their correct ones. We introduce the Epistemic Ledger, which tracks, at each turn and for each candidate answer, whether the evidence supports each constraint and whether the agent states that it holds. Evaluating 13 agents, from 7B RL-trained models to frontier LLMs, we find that constraints are left unverified in three ways: assumed without evidence, kept although refuted, or left unchecked. Training and scale improve accuracy but can increase other types of failure. Exposing each constraint's evidential state through LiveLedger, a lightweight 4B tracker, the same agents answer 4.4–16.1 points more questions correctly and fail to return a substantiated answer on 6.2–16.7 points fewer questions.

[Paper (arXiv)](https://arxiv.org/abs/2602.07549) | [Code](https://github.com/dayoon-ko/illusory_completion)
