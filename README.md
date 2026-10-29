# National-Programming-Competition-NPC-Study-Hub

A practice repository for the **National Programming Competition (NPC)** organized by the Faculty of Information and Communication Technology (FTMK) and the School of Technical Foundation and Diploma Studies (UTeM STEP) at Universiti Teknikal Malaysia Melaka (UTeM).

The NPC is a four-hour, ICPC-format programming contest using Code Judger. The poster describes 10 problems, automated judging, and a route for the top 10 teams/participants to qualify for the International Programming Competition (IPC). Check the official event information for the latest rules and qualification details.

## Event information

- **Date:** 12 December 2026 (Saturday)
- **Time:** 09:00–13:00 MYT
- **Venue:** Faculty of Information and Communication Technology (FTMK), UTeM
- **Eligibility:** Malaysians studying at IPTA or IPTS; solo competition
- **Registration fee:** RM50; includes a T-shirt and certificate of participation
- **Registration deadline shown on the poster:** 11:59 PM, Friday, 20 November 2026
- **Registration:** [prim.my/ContestPro](https://prim.my/ContestPro)

## Categories

- **Category 1:** 20 years old and below
- **Category 2:** 21 years old and above

Use the category that matches the official eligibility rules. If you are unsure how age is calculated for the event, confirm with the organizer.

## Languages

This repository includes practice templates for:

- C
- C++ (a good starting point for learning competitive programming algorithms)
- Java

Confirm which languages and compiler versions Code Judger accepts before the contest.

## Getting started

1. Choose the age category that matches the official competition rules.
2. Follow the [study roadmap](notes/roadmap.md).
3. Save each exercise under `problems/<category>/<topic>/<problem-name>/`.
4. Use a starter file from `templates/` when writing a solution.
5. In each problem folder's `README.md`, record your approach, correctness reasoning, time and space complexity, and mistakes.
6. Practice solving several problems under a four-hour time limit.

## Repository structure

```text
notes/                 Study notes and roadmap
problems/under-20/     Practice for Category 1 (20 and below)
problems/21-and-over/  Practice for Category 2 (21 and above)
solutions/             Solutions by language and topic
templates/             Starter code for C, C++, and Java
```

Example problem folder:

```text
problems/under-20/arrays/two-sum/
├── README.md
├── sample.in
└── sample.out
```

## Naming solution files

Use this format: `solutions/<topic>/<problem>/<language>/main.<extension>`. For example:

```text
solutions/arrays/two-sum/c/main.c
solutions/arrays/two-sum/cpp/main.cpp
solutions/arrays/two-sum/java/Main.java
```

## Practice principles

- Try to solve each problem yourself before reading an editorial.
- Check edge cases: minimum and maximum inputs, repeated values, and cases with no answer where relevant.
- Do not copy a solution without understanding it; explain the idea in your own words.
- Record the date, time spent, result, and what you learned.
- Practice reading problem statements and constraints carefully, then allocate contest time deliberately.

## Progress

| Topic | Status | Notes |
|---|---|---|
| Input/output and complexity | Not started | |
| Arrays, strings, and sorting | Not started | |
| Binary search and prefix sums | Not started | |
| Recursion and backtracking | Not started | |
| Stacks, queues, maps, and sets | Not started | |
| Graphs and trees | Not started | |
| Dynamic programming | Not started | |
| Four-hour contest practice | Not started | |

## Compiler setup

Install a compiler or IDE that supports C, C++, and Java. Check the compiler versions and compile commands accepted by Code Judger before contest day. Basic compile commands are included with each language template.
