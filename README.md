# Computing Careers 2026 — source bibliography and gap register

Open data from *Computing Careers 2026*, published by **Grade One**.
Licensed **CC BY 4.0**. See `LICENCE.txt`.

<https://gradeone.press/data/>

## What this is

| File | Rows | What it holds |
|---|---|---|
| `sources.csv` / `.json` | 200 | Every source the book used, graded, dated, with what it cannot tell you |
| `gaps.csv` / `.json` | 138 | Every question the book could not answer at the grade it requires |

**`sources.csv`** carries, for each source: the grade it earns under the book's
five-grade hierarchy, the date it was published, the date it was read, a
locator or a stated reason there is none, the figure it supports, and its
caveat. 75 of the 200 are grade 1.

**`gaps.csv`** carries, for each gap: the role and chapter it belongs to, what
is missing, why, and whether it is *closeable* — meaning a published source
exists and nobody has compiled it. 22 are closeable. Of the 138,
88 come from the career profiles and 50 are declared
by the chapters themselves.

## The grades

Grades run 1 to 5, best first.

| Grade | What it means |
|---|---|
| **1** | A body with the power to compel an answer, and nothing to sell you |
| **2** | An institution reporting on itself under an obligation |
| **3** | A serious survey with a published method |
| **4** | An aggregator republishing what people typed in |
| **5** | Somebody selling something |

## Why the gap register is published

Because a list of what nobody measures is more useful to a researcher than
another list of what somebody measured. Every entry marked closeable means a
published source exists and has not been compiled. Those are the cheap ones.

## Using it

Copy it, republish it, adapt it, build on it, sell something built on it. The
only condition is credit:

> Source bibliography and gap register, *Computing Careers 2026*, Grade One,
> edition 1.0.0.

**Corrections are wanted.** If a grade is wrong, a source has moved, or a gap
has been closed by something published since, write to **corrections@gradeone.press**.
Corrections that arrive with a source and a date go into the next edition, with
credit, unless you would rather not be named.

## Provenance

This directory is **generated**, not written. Every count above is recomputed by
`scripts/package.py --public` in the book's build from the files beside it, so a
number here cannot drift from the data it describes. Do not edit it by hand;
re-run the build.

Third-party material inside these files is credited where it comes from. O*NET,
published by the United States Department of Labor, and ESCO, published by the
European Commission, are used under CC BY 4.0. Neither body has reviewed or
endorsed this book.
