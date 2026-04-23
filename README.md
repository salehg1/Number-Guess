# Number Guess

Guess the hidden number between 1 and 100. Hot/cold hints guide you to the answer.

## How to Play

- Enter a number between 1 and 100 and click **$ guess** (or press Enter)
- After each guess you get a hint based on how close you are:
  - ❄ **Cold** — more than 30 away
  - **Warm** — within 30
  - 🔥 **Hot** — within 15
  - **Scorching!** — within 5
- You also get a direction hint: `↑ too low` or `↓ too high`
- Maximum **10 attempts** before game over

## Scoring

```
score = 100 - ((attempts - 1) × 10)
```

| Attempts to guess | Score |
|-------------------|-------|
| 1 (first try!)    | 100 pts |
| 2                 | 90 pts |
| 3                 | 80 pts |
| 4                 | 70 pts |
| 5                 | 60 pts |
| 6+                | 50 pts or less |
| No correct guess  | 0 pts (not submitted) |

Only correct guesses can be submitted to the leaderboard. Click **$ push_score** to save your result.
