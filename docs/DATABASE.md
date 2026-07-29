# Database Design

## Users

Stores player accounts.

Fields

- id
- username
- email
- password
- avatar
- level
- xp
- coins
- current_rank_id
- created_at

---

## Ranks

Stores all competitive ranks.

Examples

Bronze I

Bronze II

Silver I

...

---

## Matches

Stores completed matches.

Contains

- Player 1
- Player 2
- Winner
- Duration
- Match Type
- Started At
- Ended At

---

## Questions

Stores reusable templates and generated question metadata.

Contains

- Category
- Difficulty
- Question
- Answer
- Time Limit

---

## Question Categories

Examples

Arithmetic

Fractions

Algebra

Geometry

Calculus

---

## Player Answers

Stores every answer submitted during a match.

Contains

- Match
- Player
- Question
- Answer
- Correct
- Response Time

---

## Statistics

Stores player statistics.

Examples

Games Played

Wins

Losses

Accuracy

Average Response Time

Current Win Streak

Highest Win Streak

---

## Rewards

Stores unlockable rewards.

Examples

Avatars

Borders

Titles

Emotes

Themes

---

## Achievements

Examples

100 Wins

1000 Questions Solved

10 Win Streak

---

## Friendships

Stores friend relationships.

---

## Reports

Stores player reports and moderation records.
