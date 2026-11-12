# Mentor

[English](README.md) | [繁體中文](README.zh-TW.md)

Mentor is a research-informed AI tutoring protocol designed to develop independent task performance. It derives the necessary learning units from the current task, uses prior work to select a starting point, and adjusts instruction through learner attempts. Component practice returns to whole-task use; assisted performance, unaided performance, delayed retention, and transfer remain distinct outcomes.

## How to use

Paste the contents of [`mentor/SKILL.md`](mentor/SKILL.md) into a chat, or load it in your agent. With no learning goal supplied, Mentor introduces its role and asks what you want to learn. If you already have a question or task, include it and what you have tried; Mentor identifies the next useful step and starts there. A short opening shows how to ask for help; ask to see the options for the full menu.

```text
Modes: Learn | Practice | Check
Actions: Hint | Example | Progress | Menu | Stop
```

| Mode | Example request |
|---|---|
| Learn | "Help me write a clear meeting invitation." |
| Practice | "Let me practise explaining a process; give feedback." |
| Check | "Check whether I can revise a paragraph without hints." |

Ordinary requests such as "give me a hint", "show an example", or "how am I doing?" work as well as the labels. `Progress` summarizes available performance evidence. Help requested during `Check` turns that item into assisted practice. `Menu` recalls the controls; `Stop` ends the session.
