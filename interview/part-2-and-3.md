# Interviewer Prompt: Parts 2 and 3

This file is for interviewers. Give the candidate Part 2 only after they have demonstrated that their Part 1 application meets the completion criteria on `main`.

## Transition to Part 2

Paste or read this before sharing the problem:

> Part 1 is complete. For Part 2, please stop using AI tools, including chat assistants, code-completion tools that generate solutions, and agentic coding tools. You may continue to use search engines and ordinary documentation. Please share your reasoning as you work, and ask questions whenever a requirement seems unclear. You may use and modify everything already created during Part 1.

## Part 2: Analyze the Data

As a healthcare provider, we are concerned with the moods and stress levels of our patients. Use the data already available through your application to identify people who may not be doing well.

A **bad day** is a calendar day on which either:

- the user's mood is 1 or 2; or
- the user's mood is 3 and their stress level is 4 or 5.

If a mood reading is missing for a user on a date, treat the mood as 3 (neutral). A missing stress reading does not meet the high-stress condition.

Update the application to show:

1. Every user with two or more bad days during the week beginning May 7, 2017. Treat this as the seven calendar days from `2017-05-07` through `2017-05-13`, inclusive. Display the username and number of bad days, ordered from most to fewest bad days.
2. The five longest streaks of consecutive bad days in the entire dataset. Consecutive means adjacent calendar days. For each streak, display the username, start date, end date, and number of days, ordered from longest to shortest.

If multiple results have the same count or streak length, choose and explain a consistent tie-breaking rule.

Be prepared to explain:

- how you combined the three datasets;
- how you handled missing readings and dates;
- how you determined that the output is correct; and
- any assumptions or tradeoffs you made.

## Optional Part 3: Communicate the Results

Use this only if the candidate has completed Part 2 correctly and there is enough time. AI use may resume for this part.

> You may resume using AI tools. Improve the application by adding a visualization that makes one or more of the Part 2 results easier to understand. You may choose the form of the visualization. Be prepared to explain why you chose it, how you directed or corrected the AI, and how you verified that it represents the data accurately.

Part 3 is a stretch goal and should not count against a candidate who does not reach it.
