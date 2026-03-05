12-AI-Agents-Collection

This repository contains 12 small, engaging Python "agents" designed for students to learn about the GAME structure and agent loops:

G — Goals: Define success and rules for the agent

A — Actions: Python functions the agent can call

M — Memory: Small persistent state saved to JSON files

E — Environment: Executes tools and returns feedback to the agent loop

Each agent is a standalone Jupyter Notebook, demonstrating a unique interactive task. These agents are designed for learning, classroom demos, and simple experimentation.


📂 **Agents Overview**
1️⃣ **Spin-the-Wheel Study Task Picker**

**Description**: Randomly selects study tasks.

**Updates**:

Add/remove tasks during runtime

Difficulty tags: easy / medium / hard

Small leaderboard of most-picked tasks

2️⃣ **2-Minute Rescue Agent**

**Description**: Perform quick rescue operations in a simulation.

**Updates**:

Countdown timer (demo mode can shorten)

Students can add their own rescue scripts

Show best success-rate script

3️⃣ **Daily Streak Agent**

**Description**: Tracks daily activity streaks.

**Updates**:

Save minutes spent

Weekly summary

Reward messages at milestones

4️⃣ **One Line Quiz Agent**

**Description**: Quick quiz agent for single-line questions.

**Updates**:

Add confidence rating

Export results to CSV

Additional topics

5️⃣ **Flashcard Drill Agent**

**Description**: Spaced repetition for learning flashcards.

**Updates**:

Students can add cards via input

Topics and filtering

Simple spaced repetition

6️⃣ **Notes Cleaner Agent**

**Description**: Cleans and formats notes into structured output.

**Updates**:

Detect headings (with ':') and convert to Markdown

Timestamped output files

Summary template section

7️⃣ **Bug Hunt Bingo Agent**

**Description**: Gamified bug detection using a bingo-style card.

**Updates**:

Detect Bingo (row/col/diag) and celebrate

Students can customize bug list

Export card to a text file

8️⃣ **Tiny Mentor Agent**

**Description**: Simple mentorship and challenge agent.

**Updates**:

Modes: strict / friendly / QA

Streak counter

Students can add custom challenges

9️⃣ **Reminder Agent**

**Description**: Multi-reminder management tool.

**Updates**:

Multiple reminders in a list

Status command

Reminder logs

🔟 **Decision Agent**

**Description**: Helps make decisions between options.

**Updates**:

Add a third option

Confidence rating

Review last decision

1️⃣1️⃣ **Assignment Breakdown Agent**

**Description**: Breaks assignments into manageable parts.

**Updates**:

Ask for available time and adapt plan

Export to Markdown

Review last plan

1️⃣2️⃣ **Q/A Ticket Agent**

**Description**: Manages Q/A tickets efficiently.

**Updates**:

Save each ticket as its own text file

Add urgency field

Share-ready formatting

**Features Across Agents**

Simple Python functions to simulate an agent decide → act → observe → repeat loop

Minimal coding for quick learning and experimentation

Persistent state using JSON files for memory

Demo mode (DEMO_MODE=True) to shorten waits and timers

Extensible: students can add tasks, cards, reminders, or challenges depending on the agent
