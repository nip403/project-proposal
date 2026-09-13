# Housemate Manager

## What and why?

Living with roommates often means unbalanced chore loads and shared expenses, potentially leading to tension and damaged relationships.

Housemate Manager is a shared web app that removes the emotional friction of holding roommates accountable. It automates chore rotation, requires photo proof of completion, and keeps a running expense ledger to protect users' time, money, and relationships.

## For whom?

College students and young professionals sharing a home. The initial focus is university students in 2-5 person leased apartments.

## How?

- **Onboarding**: A user creates a "House" and shares a join link with roommates.
- **Chore engine**: The house builds a list of recurring tasks and how often they repeat. The app auto-assigns and rotates them among roommates each week, probably using a cron-based scheduler. Tasks can be flexibly assigned to a selection of users, or between all users.
- **Accountability**: Completing a task requires a photo for verification. On-time completions earn points toward a monthly leaderboard, turning accountability into friendly competition. Incentives/disincentives can be tuned as we go.
- **Shared ledger**: Instead of splitting every purchase individually, roommates log shared expenses into the app, which tracks amounts owed and lets everyone settle up in one go at month's end.

## Scope

Achievable for a team of 4–6 over one semester.

A potential concern would be the security of image handling for chore verification.