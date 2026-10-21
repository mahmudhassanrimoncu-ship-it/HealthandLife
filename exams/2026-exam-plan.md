# Exam plan: 3rd-semester finals (Nov 2026), with retake windows protected

Version 2, 21 Oct 2026. Built on Rimon's answers:
- Retakes to sit: **EEE-221 theory (Thu 29 Oct), EEE-222 lab (Sun 22 Nov), MAT-235 (Thu 26 Nov).** Rimon handles these; this plan only protects their time.
- **Failing a special retake means losing the seat at CU.**
- Every 3rd-sem course is currently at **level 1** ("heard of it").
- Very few class tests were taken; expect **about 0** in-course marks.
- The 3rd-sem routine is **not published** yet. Finals are expected from 5 Nov.

The goal: **pass as many 3rd-sem papers as possible without risking a retake and without triggering the crash cycle.**

---

## 1. The honest numbers

Theory papers are 10% attendance + 20% class tests/assignments + 70% final. Assuming CU's usual pass mark of 40% overall (confirm this):

| Your in-course marks | What you need in the 70-mark final |
|---|---|
| 0 CT, ~3/10 attendance | **~37/70, about 53% of the paper** |
| 5 CT/assignment marks, ~3 attendance | ~32/70, about 46% |
| 10 CT/assignment marks, ~3 attendance | ~27/70, about 39% |

So **any in-course mark you can still recover is worth a lot.** Ask each course teacher whether a missed CT or an assignment can still be submitted. Five marks now lowers the bar in the final noticeably.

Starting from level 1 everywhere, with about two weeks before finals start (one of which belongs to EEE-221), **passing all five theory papers is unlikely. Passing three or four is realistic if you follow the pacing rules and use past papers.** University finals repeat question types heavily, and that repetition is what makes this possible.

---

## 2. The one rule that overrides everything

**A retake always beats a 3rd-sem paper.** Failing a 3rd-sem paper costs a later retake. Failing a special retake costs your place at the university. So these windows are blocked for retakes, whatever the 3rd-sem routine says:

| Window | Belongs to |
|---|---|
| 21 to 29 Oct | EEE-221 theory |
| about 18 to 22 Nov (2 to 3 days) | EEE-222 lab |
| about 21 to 26 Nov (4 to 5 days) | MAT-235 |

If a 3rd-sem paper lands inside one of these windows, it gets only floor-day effort (one short block on the day before).

**Ask the department now:** what happens if you are too ill to sit a special retake on the day? Is there a medical route? Get the answer in writing (a message is fine). With fainting episodes and multi-hour bathroom sessions on record, this is not a theoretical question.

---

## 3. Department actions (do these this week, in one message)

1. **DLD lab final (CSE 322):** request a make-up. You missed it because of an acute reaction on the first morning of Prodep. Ask your psychiatrist for a short note confirming the start date and the reaction.
2. **Medical route for special retakes** (section 2).
3. **Missed CTs/assignments:** can any still be submitted, per course?
4. **Pass mark and promotion rule** for 3rd sem: confirm 40%, and ask whether failing 3rd-sem papers affects promotion.
5. **The 3rd-sem routine** as soon as it is out, and who to tell about clashes with retake dates.
6. **Past final questions** (last 3 to 5 years) for CSE 311, CSE 321, MAT 331, STA 351, ECO 381 and the labs, from seniors, the CR, or the photocopy shops near campus.

---

## 4. Pacing (unchanged, and the most important part)

| Day type | What you do |
|---|---|
| **Floor day** (crashed, foggy) | 1 block of 15 min. One question and its answer. Counts as a success. |
| **Normal day** | 3 blocks of 25 min, 10+ min lying down between. Done by early evening. |
| **Good day** | **Max 5 blocks. Stop even if you feel great.** This is what prevents the 3-to-7-day crash. |
| **Exam eve** | 2 light review blocks. No new topics. Early night. |

**Inside a block:** phone in another room. One past question. Read the solution. Close it. **Write it yourself by hand.** Check it. **Stuck for 5 minutes: mark it and move on.**

**Around the bathroom:** plan blocks as "after the bathroom, rest 15 minutes, then a block", never by clock time.

**One exam at a time:** gap days between papers go to the next paper only.

---

## 5. Block budget

Realistically, between 30 Oct and the end of Nov you have maybe **45 to 55 blocks** for the 3rd sem once crash days and retake windows are taken out. This is how they are split. Each course's "pass core" below is sized to fit.

| Course | Credits | Blocks | Priority | Why |
|---|---|---|---|---|
| MAT 331 Linear Algebra & Optimization | 4 | **12** | 1 | Biggest course. Mostly fixed procedures you can drill. |
| CSE 311 Data Structures | 3 | **10** | 1 | Core of the degree. Section B is almost all hand-tracing. |
| CSE 321 Digital Logic Design | 3 | **9** | 2 | Mechanical (K-maps, adders, flip-flops). |
| ECO 381 Economics | 3 | **5** | 2 | No maths. Best marks per block. Last 2 days before its exam only. |
| STA 351 Probability Models | 3 | **6** | 3 | Hardest paper. Aim for a bare pass. Sacrifice first if needed. |
| CSE 312 DS Lab | 2 | 4 | 2 | Same content as CSE 311, written as code. |
| CSE 314 Problem Solving Lab | 2 | 3 | 2 | A handful of standard programs. |
| CSE 322 DLD Lab | 1 | 2 | 3 | Only if the make-up is granted. |

---

## 6. Pass core for each course (from the syllabus, to be checked against past papers)

Block counts are in brackets. Past papers overrule this list: if a skipped topic repeats every year, swap it in for a weaker one.

### MAT 331 Linear Algebra and Optimization (12 blocks)
**Section A**
- Gaussian elimination, row echelon form, solving a system (2)
- Checking linear independence (1)
- Inverse of a matrix by row reduction; determinants and Cramer's rule (1.5)
- Null space, column space, rank and nullity, basis (1.5)
- **Eigenvalues, eigenvectors, diagonalization**, 2×2 and 3×3 (2)
- Gram-Schmidt (0.5)

**Section B**
- Refresh partial derivatives (0.5)
- Critical points: gradient = 0, Hessian / second-derivative test (1)
- Lagrange multipliers (1)
- Least squares via the normal equations AᵀAx = Aᵀb (1)

**Skip:** SVD, spectral theorem proofs, convex-set theory, geometric programming, KKT.
Your weak maths basics matter less than you fear here. Most of this is careful arithmetic in a fixed order.

### CSE 311 Data Structures (10 blocks)
**Section A**
- Insertion sort, merge sort, quick sort: trace on a given array, plus their time complexity (2.5)
- Binary search (0.5)
- Stack and queue operations, circular queue, **infix to postfix and postfix evaluation** (2)
- Singly and doubly linked list insert/delete, drawn as box diagrams (1)

**Section B**
- **BST insert, delete, inorder/preorder/postorder** (1.5)
- Build-max-heap, heapify, heapsort traced on an array (1)
- BFS and DFS order on a given graph (0.5)
- **Prim's and Kruskal's** traced on a given graph (1)

**Skip:** interval trees, dynamic order statistics. Disjoint sets only if past papers show it.

### CSE 321 Digital Logic Design (9 blocks)
**Section A**
- Number system conversions, signed numbers, 2's complement, BCD, Gray code (1.5)
- Boolean algebra laws, De Morgan, simplification (1)
- **K-maps, 3 and 4 variables, SOP and POS, with don't-cares** (2)
- Half adder, full adder, ripple-carry adder, 2's complement adder/subtractor (1)
- Decoders and encoders; implementing a function with a decoder (0.5)

**Section B**
- Multiplexers; implementing a function with a MUX (1)
- SR, D, JK and T flip-flops: characteristic and excitation tables (1)
- Synchronous counter design (1)
- Definitions only: propagation delay, Mealy vs Moore, clock skew, metastability (part of a block)

**Skip:** Quine-McCluskey (unless it repeats), full FSM design, ROM/PLA, Verilog.

### STA 351 Probability Models and Inference (6 blocks, bare-pass target)
**Section A**
- Joint and marginal distributions, discrete tables first (1.5)
- MGFs: definition, for binomial/Poisson/exponential, using them for mean and variance (1)
- Poisson process and the exponential distribution, the memoryless property (1)
- **Markov chains:** transition matrix, n-step probabilities, steady state (1.5). This is solving linear equations, the same skill as MAT 331.

**Section B**
- Bayes' rule, posterior, MAP rule (1)
- Short-note definitions for easy marks: Monte-Carlo vs Las-Vegas algorithm, Bayesian vs classical inference (part of a block)

**Skip:** convergence of random variables, Chernoff bounds, balls-and-bins, hashing analysis, skip lists.

### ECO 381 Economics (5 blocks, last 2 days before its exam)
Prepare about 12 model answers, each with a diagram and, where possible, a Bangladesh example:
- Demand and supply, equilibrium; price elasticity (types and formula)
- Opportunity, sunk and marginal cost
- Perfect competition vs monopoly vs oligopoly (as one comparison table)
- Externalities and public goods; bounded rationality and nudges
- GDP; inflation and CPI; types of unemployment
- Fiscal vs monetary policy; central bank tools; exchange rates
- Tariffs and arguments for protection

### Labs
- **CSE 312 (4 blocks):** after CSE 311 theory, write from scratch: stack, queue, singly linked list insert/delete, BST insert/search/traversal, BFS/DFS on an adjacency list, merge sort or quick sort.
- **CSE 314 (3 blocks):** reading C declarations and pointers; STL basics (vector, sort, map, set, pair); GCD, sieve of Eratosthenes, fast modular exponentiation; cross product for geometry.
- **CSE 322 (2 blocks, if the make-up is granted):** truth-table verification, adder and counter circuits, one small Verilog module, standard viva questions.

---

## 7. Calendar until the routine is out

| Dates | What |
|---|---|
| 21 to 28 Oct | **EEE-221 only.** For the 3rd sem, only the department message and collecting past papers. No 3rd-sem content this week. |
| Thu 29 Oct | EEE-221 exam |
| Fri 30 Oct | Rest. No study. |
| 31 Oct to 4 Nov | Start the **first 3rd-sem paper in the routine**. If the routine is still not out, start **MAT 331**: it is the biggest course and it feeds STA 351 (Markov chains) and possibly MAT-235. |
| From 5 Nov | Exam by exam, using the block budget. Rebuilt the day the routine is published. |

---

## 8. How I can help inside a block

- Send a photo of a past-paper question: I'll solve it step by step and give you a similar one to try yourself.
- Ask for a one-page cheat sheet for any topic above.
- Ask for a 5-question quiz on what you did yesterday. Recall is what makes things stick.

---

## 9. Exam-day checklist

- **Night before:** admit card, ID, pens, calculator, water, snack, and cash for a bus or CNG in case you miss the shuttle. Bag at the door.
- **Wake-up time:** work backwards from the start time using your *worst* recent bathroom time plus the commute.
- **Eat** before you leave.
- **Dozing in exams:** ask your psychiatrist before 29 Oct what can be done about daytime sleepiness in exam weeks. Do not change your medicine yourself.
- **Tea and coffee:** go easy. Fluvoxamine (Voxamin) slows how fast the body clears caffeine by a large amount, so one cup lasts far longer than usual and can wreck that night's sleep.
- **In the hall:** answer what you know first. Stalled for 5 minutes, move on.

---

## 10. Tracking

Each evening, reply in the thread with one line and it gets logged here:

`date | floor/normal/good | blocks done | sleep hours | longest bathroom time | note`

---

## Still open
- Can you get **past final questions** for the 3rd-sem courses?
- (Optional) What topics does **MAT-235** cover? If it overlaps with MAT 331, one study session serves both.
