# Math Engine

## Overview

The Math Engine is responsible for generating all math questions in the game.

Questions must never be hardcoded.

Each question is generated dynamically based on the player's difficulty tier.

Each generated question returns:

- Question
- Correct Answer
- Category
- Difficulty
- Time Limit
- Accepted Answer Format

---

# Grade 1

Topics

- Addition
- Subtraction

Number Range

1–20

Question Examples

8 + 5

14 - 7

Answer Format

Integer

Time Limit

15 seconds

---

# Grade 2

Topics

- Multiplication
- Division

Number Range

1–100

Question Examples

12 × 6

96 ÷ 8

Answer Format

Integer

Time Limit

12 seconds

---

# Grade 3

Topics

- Fractions
- Basic Word Problems

Question Examples

1/2 + 1/4

Sarah has 8 apples...

Answer Format

Fraction or Integer

Time Limit

20 seconds

---

# Grade 4

Topics

- Decimals
- Percentages

---

# Grade 5

Topics

- Geometry
- Ratios

---

# Grade 6

Topics

- Algebra Basics

---

# High School

Topics

- Algebra
- Geometry
- Trigonometry

---

# College

Topics

- Calculus
- Statistics
- Matrices
- Linear Algebra

---

# Question Rules

Questions are generated randomly.

The same question should rarely appear twice.

Questions must be validated on the server.

Questions are never generated on the client.

---

# Accepted Answer Types

- Integer
- Decimal
- Fraction
- Mathematical Expression (Future)

---

# Future Expansion

Support:

- Handwriting Recognition
- AI Generated Word Problems
- Multiple Correct Answer Formats
- Adaptive Difficulty
