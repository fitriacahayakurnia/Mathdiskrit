---
title: UAS

---

**1.**

| NO | P  | Q  | R  | S  | P → Q| (P → Q) → (R → S)|
|--- | ---| ---| ---| ---| -----| ---------------- |
|1.  | T  | F  | F  | F  | F    | T                |
|2.  | F  | F  | T  | F  | T    | F                |
|3.  | T  | F  | T  | F  | F    | T                |
|4.  | F  | F  | F  | F  | T    | T                |
|5.  | T  | T  | T  | T  | T    | T                |
|6.  | F  | T  | T  | T  | T    | T                |
|7.  | F  | T  | F  | T  | T    | T                |
|8.  | T  | T  | F  | T  | T    | T                |



**2.** ![](https://cdn.mathpix.com/snip/images/qUpdBQtTVpr0NkOp0-4tlPPy5VXCQ64ncHFG0TIfK6w.original.fullsize.png)
**Hitung Closeness Centrality**
| Node | A | B | C | D | E | F | G |
|---   |---|---|---|---|---|---|---|
|A     | 0 | 1 | 1 | 2 | 2 | 1 | 3 |
|B     | 1 | 0 | 1 | 2 | 2 | 1 | 1 |
|C     | 1 | 1 | 0 | 3 | 2 | 2 | 4 |
|D     | 2 | 2 | 3 | 0 | 1 | 1 | 1 |
|E     | 2 | 2 | 3 | 1 | 0 | 1 | 1 |
|F     | 1 | 1 | 2 | 1 | 1 | 0 | 1 |
|G     | 3 | 3 | 4 | 1 | 1 | 2 | 0 |

CC(G)=(7-1)/(3+3+4+1+1+2)=6/14=0,42

**Hitung Betweenness Centrality**

Pasangan (s, t) dan kontribusi F:
- A → G: A → F → G, kontribusi = 1
- B → D: B → F → D, kontribusi = 1
- C → D: C → F → D, kontribusi = 1
- C → E: C → F → E, kontribusi = 1
- D → E: D → F → E, kontribusi = 1

CB(F) = 1 + 1 + 1 + 1 + 1 = 5
