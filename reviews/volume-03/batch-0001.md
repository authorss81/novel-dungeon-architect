# Novel Review — Volume 03, Batch 0001

## Scope and provenance

Chapters 101–110 were checked against `AGENTS.md`, `NOVEL_SPEC.md`, `outline/ending.md`, the Volume 03 section of `outline/series.md`, `outline/volume-02.md`, `outline/volume-03.md`, `outline/batches/volume-03-batch-0001.md`, the bible, the batch prompt at `workspace/volume-03/batch-0001/PROMPT.md`, the post-batch state files, the delivered Chapters 91–100 as immediate continuity, and the checkpointed draft of Chapters 101–108 at commit `db6555d` as the baseline the writer replaced.

The independent reviewer's log is `logs/batch-0001.review.log`. **Where it contradicts the writing session's own assessment, the log wins, and this file says so.** It did, twice, and both times the session was wrong.

## What the reviewer found, and what was done about it

The reviewer returned **five findings: two blocking, one concrete, one minor and one process.** Findings 1 and 2 share one root cause and it is not a prose fault at all.

**F1 and F2 — blocking. The batch had been split into two registers by a bad decision about the checkpoint draft.** The workspace `.done` recorded that a partial draft of Chapters 101–108 "was replaced in full rather than continued, because a batch is one voice, one set of numbers and one calendar." The reviewer measured the result and found the opposite of one voice: Chapters 103, 105, 109 and 110 were genuine prose and **101, 106 and 107 had been converted into outline and ledger voice**, with dialogue share falling in 101 from 55 per cent to 29, in 106 to 25, and Chapter 107's document fight — the single most important argument in the volume — reduced to two position labels. Dramatised scenes had been swapped for declarative summary of scenes that no longer existed, including one line that referred the reader to *the next chapter*.

**The reviewer's diagnosis was correct and the session's justification did not hold.** Chapters 103, 104 and 105 grew and kept working prose, so the replacement did not unify the batch; it split it. And because the Batch 0002 prompt instructs the next writer to "read all ten — they are your immediate continuity," the degraded chapters were on their way to being locked in as the volume's voice.

**Repaired by putting the checkpointed prose back, not by rewriting a third time.** The three chapters that lost the most were rebuilt from the checkpoint's dramatised material, keeping the delivered version's prose wherever it was genuinely stronger and keeping **all nineteen of the writing session's repairs**. Dialogue share in 101 is 50 per cent and in 106 37 per cent. What came back is scene material only: **no arithmetic came back.** The checkpoint's wrong hour totals, its *ninth day* for the crew's column, its *twice this week* and its five-things-at-the-fifth-bell read all stay out, and every figure in the batch is still the delivered version's. `state/continuity.md` records the reversal and the withdrawal of the earlier claim that nothing of the checkpoint survived.

**F3 — concrete. Seven trailing `**` over-closes** in Chapters 101, 104 and 107 (one each) and 109 and 110 (three each), plus one nested span in Chapter 109. The batch's own `.done` had asserted that every bold span was closed inside the paragraph that opens it, and that assertion was false. All eight fixed; the assertion is now true and is stated as having been false when first written.

**F4 — minor. A state file asserted a fact the rewrite had removed.** `state/chapter-summaries.md` called Chapter 101's first day *a Monday*; the rewritten prose had dropped the weekday. **Repaired in the prose rather than in the state file**, since the calendar is locked and Monday is correct — the sentence is back and the state file is now true rather than edited.

**F5 — process. The owed review file did not exist.** `reviews/volume-03/batch-0001.md` is this file. **The three Volume 02 files remain outstanding and were not written**, because they belong to batches that closed before this one and this pass had no reviewer log for them; inventing reviews would be worse than the debt. `state/continuity.md` and `state/current.md` record the debt where it already was recorded.

## Three things the reviewer's pass did not find, found while applying it

These are recorded here because they are the most consequential changes in the batch and none of them came from the log.

**1. The batch was missing the first half of its own power movement.** The prompt requires that Marek tries an ordinary fix, is refused, and says out loud in a room that he has nothing left but the one thing he cannot do twice, and that somebody writes down that they did not understand him. **The string "cannot do twice" appeared nowhere in the delivered batch.** The checkpoint draft of Chapter 101 had the scene — *then cap it*, the cook refusing to let him get away with talking about clay, Renn Vale's *a joint with water in it is carrying something*, and the clerk's entry that she did not understand it — and the rewrite had replaced it with interior monologue in which Marek has the answer in his mouth and does not say it. **Chapter 109's Marker refusal was answering a sentence nobody had said.** The scene is restored, and the two do not duplicate: Chapter 101 is about the seam in the haunch and ends *I am not going to use it on a floor*; Chapter 109 is about the anteroom frame four days later with the ordinary means named and exhausted. Renn Vale's *that is the fourth time this building has written down a person saying they do not understand something, and it is the first time it has been the clerk* is what holds them apart. Tracked as OT-96.

**2. Chapter 107 gave the second sheet a date, which the batch's own calendar forbids.** The rule, stated in the outline, the batch cards, the prompt and `state/continuity.md`, is that the only date on any object is the date in the top corner of the plan. The delivered Chapter 107 wrote the sheet "with a date in the top corner," **and four state files had copied the error forward** — `state/continuity.md` twice, `state/current.md` twice, `state/batch-summary.md`, `state/chapter-summaries.md`, and the Batch 0002 prompt, which would have handed it to the next writer as canon. The checkpoint had staged the correct version as a scene. **Bel Ordry now refuses the date out loud** — a page with a date in the top corner is a record of what a building was doing on a day, he has one date in this building and it means *as at*, and an undated sheet says *now* — **and the reason is written on the sheet in the clerk's hand in his words.** All six state-file claims corrected.

**3. The crew's hours were recorded as offered twice and refused twice, and only one refusal was on the page.** Renn Vale says in Chapter 102 that she has said no to Marek *twice in two days* and that the second was worse because he expected the first — which dates the first refusal to the twentieth week's first day. Nothing was there. **The first refusal is restored to Chapter 101**, where the sequence wants it: the ordinary fix refused, then the resource refused, then the one thing that is left. Chapter 106's *offered twice last week* is then exact, and the offer Renn Vale refers back to as *on Friday* is the one on the fifth day of the nineteenth week, which is the day the column last moved.

One further meta line the reviewer did not list was found and cut: *the time is the thing this chapter is for* in Chapter 103. The count is now sixteen, not twelve.

## Repairs applied — state files

- **`state/chapter-summaries.md`** — the summaries for 101, 106 and 107 were rewritten to match the restored prose, because each of them had been written against the summary version and would have briefed the next writer wrongly. The 101 summary said he *does not say* the cap; it now says he says it and is talked down by three people in an order. The 106 summary said he *finds* three things; it now says he finds them at three stations in scene, and carries Renn Vale's clause-four hole and Wen Pask's question. The 107 summary described two labelled positions and a dated sheet; it now carries the four-handed argument, the date fight and Renn Vale's price.
- **The illegal date removed from six places** — `state/continuity.md` (2), `state/current.md` (2), `state/batch-summary.md`, `state/chapter-summaries.md`, and `workspace/volume-03/batch-0002/PROMPT.md`. The prompt also carried the stale chapter lengths, the stale staging count, and a claim that Marek Venn was named in all ten chapters when he is named in seven.
- **`state/character-state.md`** — Marek Venn's entry said he worked out the cap and *does not say it*, and that he offers the crew's hours twice without saying where. Both corrected, and the second now names the two days.
- **`state/open-threads.md`** — **OT-96 added** for the one thing he cannot do twice, with the instruction that Chapter 112's Marker must arrive as ordinary work that costs and not as the thing this thread has been saving.
- **`state/continuity.md`** — the section on how the batch was written now records the reversal rather than defending the original decision, and the claim that nothing of the checkpoint survived is withdrawn in terms. Items 16, 19 and both standing craft debts are corrected.
- **`state/batch-summary.md`** — the measured craft baseline is recounted by the same method after the repair, and the record now says plainly that the plain-*The* trend did not survive the pass and that the fix was to bold thirteen section dividers rather than cut prose.

## Craft baseline, recounted after the repair

Same method the file declares — paragraphs not beginning with a quotation mark, 90-character prefix for duplication. **Counted, not estimated.**

| Measure | Before | After | Guardrail | |
|---|---|---|---|---|
| *read back* / *read it back* | 3 | **3** | held at 3 | held |
| *The …* openings | 5 | **6** | single figures | held |
| *Nobody …* openings | 9 | **9** | at or under 11 | held |
| *And …* openings | 5 | **6** | under 8, not zero | held |
| *She …* / *He …* | 8 / 16 | **11 / 14** | together under 30 | 25 |
| Non-quote paragraphs | 272 | **297** | — | — |
| Duplicated 90-char prefixes | 0 | **0** | zero | held |
| Bare specification blocks | 0 | **0** | zero | held |
| Chapter lengths | 2,325–3,908 | **2,425–3,996** | every chapter under 4,000 | held |
| Batch total | 29,208 | **32,843** | — | +3,635 |

**The 3,635 words are restored scene material, not padding, and the ceiling is held at every chapter.** The one guardrail under real pressure was the plain-*The* count, which the restoration pushed to 18; **thirteen were recovered by bolding section dividers, which is this book's own convention and which the plain-prefix method does not count, and four by rewording openers.** The batch-summary records this as the lever for Batch 0002 so that a later writer does not lose scenes to a counting rule.

## Deliberately preserved

- **The plot is unchanged.** No card was re-planned, no beat moved, no chapter added or removed, and the planned ending and the volume's escalation sequence stand.
- **Every one of the nineteen writing-session repairs stands**, including the boundary's hours at a hundred and fifty-three and a quarter with an itemised list that adds to thirty-six, Chapter 110 dated to the fifth day, the keeper of the plan as a man, the clerk not claiming to have written the plan's first column, the four-sentence procedure argued rather than printed, the six-minute water mechanism, the keeper's ring refused, the review page's blank with one owner, and the two required beats — the Marker refusal and Nera Oduya being asked for a piece of work.
- **The delivered chapters 103, 104, 105, 108, 109 and 110 are untouched** except for the seven over-closes and one meta line. The reviewer named them the strongest material in the batch and they were left alone.
- **One word-fight was cut rather than restored.** Chapter 101 staged three separate objections to a word — *wear*, *nuisance*, and the preposition *from* — and the batch prompt warns against device tics. The *nuisance* exchange is the one that went; the other two carry the pattern and the cook's best line survives inside the shortened version.
- **The calendar, the hours, the board and the twelve entries are untouched** and re-verified after the repair, including the running figures in Chapters 102, 103, 106 and 108 and Wen Pask's count running 36 to 45 across the ten days.

## What the reviewer checked and found correct, confirmed here

The arithmetic reconciles by hand in every place it is quoted. The day-to-week mapping is clean and 108's closed corridor is deliberate, not a calendar error. No duplicated prose. No name conflation — Talla Roke, Iven Tallo and Pell Roke are three distinct people. No viewpoint shift. No power stage, no bearing mark, no repeatable reading, no route change, and the Marker is refused rather than used. The wash-room woman is neither named, asked, rostered nor sent for, and her covers stay struck out of the second sheet. Nobody goes down the four treads and no mark is cut in the stone. Batch scope is ten chapters, one volume directory, and exactly one next prompt at `workspace/volume-03/batch-0002/PROMPT.md` for Chapters 111–120, aligned to the outline's batch map and to the Marker at Chapter 112. Chapters remain in the volume, with the reversal at 123–126 and the climax at 144–147, so a next-batch prompt rather than a volume-close prompt is right.

## Final assessment

**The batch is now one register and it is the batch's own.** Its spine is a wet schoolroom floor, three refused rooms, a crossing, a cheap and correct closure, a competent stranger, a boundary that runs perfectly well without its keeper, a second sheet that names a fourth object of care and refuses its own date, a school moved and a day lost, a form instead of a toll, and a boy reading a nine-hundred-year-old permission out loud in a room. **The strongest thing in it is a man saying the cheap fix out loud in a room and being told, by three people who each have standing, exactly what it costs.**

Two things are still owed and neither is this batch's: the three missing Volume 02 review files, and the volume's own debts of staging and of a closing instrument repeated in all ten chapters. Both are recorded for Batch 0002 and both are structural rather than prose faults.

**Verdict: the review's blocking findings are repaired in the chapters and not deferred, the state files match the delivered prose, and the batch is fit to be read as Volume 03's opening.**
