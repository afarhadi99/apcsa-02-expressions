# AP CSA — Assignment 02: Expressions & Debugging
**Sessions 6–8 · Sep 22, 23, 24**

Arithmetic, integer division, casting, and the single most valuable skill in programming: finding your own bugs.

---

## Exercises

| # | File | Session | What you're doing |
|---|---|---|---|
| 1 | `src/ChangeMaker.java` | 6 | Quarters, dimes, nickels, pennies with `/` and `%` |
| 2 | `src/TimeConverter.java` | 6 | Seconds → H:MM:SS |
| 3 | `src/DigitExtractor.java` | 6 | Pull digits out of a number |
| 4 | `exercises/01-arithmetic.md` | 6 | Predict-then-run |
| 5 | `src/SplitTheBill.java` | 6 (HW) | Shares plus leftover cents |
| 6 | `src/TipCalculator.java` | 7 | Rounding to 2 decimals |
| 7 | `src/TemperatureConverter.java` | 7 | F ↔ C |
| 8 | `src/AverageCalculator.java` | 7 | ⚠️ Integer division trap |
| 9 | `exercises/02-casting.md` | 7 | Overflow lab |
| 10 | `src/GradeAverage.java` | 7 (HW) | Weighted average |
| 11 | `src/DebugMe1.java` – `DebugMe5.java` | 8 | The debugging gauntlet |
| 12 | `PROJECT-IDEAS.md` | 8 (HW) | Three project ideas |

---

## The two rules that will save you the most time

**1. Integer division truncates.**
```java
7 / 2       →  3      NOT 3.5, NOT 4
(double) 7 / 2  →  3.5
```
Cast **before** you divide, not after.

**2. Debug one change at a time.**
```
READ the error → LOCATE the line → PREDICT the cause
→ CHANGE one thing → RE-RUN → repeat
```
Changing five things and re-running isn't debugging, it's guessing.

---

## Before you submit
- [ ] Every program runs
- [ ] `exercises/01-arithmetic.md` predictions filled in **before** you ran the code
- [ ] `PROJECT-IDEAS.md` complete with a marked top choice
- [ ] 3+ commits, real messages
- [ ] Fork URL in Google Classroom
