# FCAIH Algorithms Task 4 — Birthday Cake Candles (Three Approaches)

An academic algorithms assignment comparing **three different algorithmic approaches** to solve the "Birthday Cake Candles" problem — count how many candles have the tallest height in a given list.

## Tech Stack

- **Languages:** C (algorithms #1, #2), C++ (algorithm #3)
- **Documentation:** Microsoft Word (.docx) and PDF
- **Platform:** HackerRank-style problem

## The Problem

Given a list of candle heights (integers), count how many candles have the maximum height. Example: `[4, 4, 1, 3]` → tallest is `4`, count = `2`.

## Three Algorithms Compared

| # | Approach | Time Complexity | Space | Passes |
|---|---|---|---|---|
| 1 | Non-recursive (two-pass) | O(n) | O(1) | 2 (find max, then count) |
| 2 | Non-recursive (single-pass) | O(n) | O(1) | 1 (track max and count simultaneously) |
| 3 | Recursive | O(n) | O(n) stack | 2 phases (find max during descent, count during ascent) |

### Key Insights
- **Algorithm #2** is optimal: single pass, constant space, no overhead
- **Algorithm #1** is simpler but does two passes
- **Algorithm #3** demonstrates recursive thinking but has O(n) stack space overhead

## File Structure

```
FCAIH_Alglorithms_Tasks/
├── Algorithms Task 4.pdf     # Full problem description, code, pseudocode, analysis
├── Algorithms Task 4.docx    # Same content in Word format
└── README.md
```
