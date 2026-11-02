# Bayesian Calendar

A personalized study planner that uses a Bayesian network to decide how to schedule
study sessions before an exam, then books the chosen action in Google Calendar.

## Status
Work in progress (course project, Option 3: Bayesian Calendar, 1-person option).

## Planned structure
- `src/bayes_net.py`: Bayes net variables, structure and handcrafted CPTs (pgmpy)
- `src/decision.py`: actions, utility function, expected utility, best action
- `src/calendar_api.py`: Google Calendar API (create/delete events)
- `src/scenarios.py`: simulated students (struggling vs. advanced, exam near vs. far)
- `src/main.py`: runs a scenario end to end
- `docs/`: model design, CPT explanations, inference task

## Setup
```
pip install -r requirements.txt
```
Google Calendar credentials (`credentials.json`, `token.json`) are not committed.
