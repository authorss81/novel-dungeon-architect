One review file per completed batch, named `<volume>-<batch>.md` — for example `volume-01/batch-0001.md`.

A review file records the scope checked, every repair applied, what was deliberately preserved, and the final assessment. It is the artifact that lets `NOVEL_SPEC.md` and `state/batch-summary.md` claim a batch was independently reviewed: if a batch is described as reviewed anywhere in the repository, its review file must exist here.

Where an independent review log contradicts the authoring session's own assessment, the log wins, and the review file says so.

## Independence, and how to tell what a file is

**A review file is not automatically a verdict.** A file written by the author of the prose, inside the author's own commit, in the author's own session, is a **self-review**, and a repository reader must be able to tell the difference from the directory listing alone without opening the file. Three rules, all binding:

- **A self-review carries `SELF-REVIEW` in its own first heading line**, in capitals, alongside the words *not a verdict*.
- **A self-review's first paragraph says in plain words that it was written by the author of the chapters it describes, and that the batch has not been independently reviewed.** Not a footnote, not a closing line — the first paragraph.
- **No batch may be described as independently reviewed anywhere in the repository — in a state file, a summary, a prompt or a hand-over — unless an independent review exists.** Where one is owed and not delivered, the debt is named in the state files and in the next prompt rather than left to be discovered later.

**Where the review owed is still outstanding, it is named here.** The register below is the authoritative one for this repository, and it is updated when a review lands, not when a batch is written.

| Batch | Chapters | Status |
| --- | --- | --- |
| Volume 04, Batch 0001 | 151–160 | self-review on file |
| Volume 04, Batch 0002 | 161–170 | self-review on file |
| Volume 04, Batch 0003 | 171–175 | self-review on file |
| Volume 04, Batch 0004 | 176–180 | **the only Volume 04 batch with an independent review behind it.** Its file holds two records: the writer's self-review in the first half, and a repair pass in the second that folded in findings from a review the writer did not control. That review is the source of the four craft rules that Batches 0005 and 0006 were written under |
| Volume 04, Batch 0005 | 181–185 | self-review in the first half; **an independent review was run in a phase the writer did not control and its findings are folded into a repair pass in the second half of the same file.** Five chapters were rewritten in place |
| Volume 04, Batch 0006 | 186–192 | **SELF-REVIEW, not a verdict. Repaired once after a review returned seven findings against the record's own measurement layer; the prose and continuity were not at issue and six of the seven were real. An independent review of this batch is still owed.** |
| Volume 04, Batch 0007 | 193–197 | **SELF-REVIEW, not a verdict — the volume's climax batch. Written by the writer of the five chapters inside the writer's own commit. Its own first line carries `SELF-REVIEW` and `not a verdict` so that a reader scanning this directory can tell what the file is from the listing alone. An independent review of this batch is still owed, and the file that follows this one is not one.** |
| Volume 04, Batch 0008 | 198–200 | **SELF-REVIEW, not a verdict — the volume's resolution batch and the batch that closes Volume 04. Written by the writer of the three chapters inside the writer's own delivery session, in the same session that drafted and repaired them. Its own first heading line carries `SELF-REVIEW` and `not a verdict` so that a reader scanning this directory can tell what the file is from the listing alone.** **The file is now a two-part document: an independent review was run in a phase the writer did not control, `logs/batch-0008.review.log`, and its findings are folded into a repair pass in the second half of the same file. It returned nine findings — four prose defects (an internal count contradiction in Chapter 200, a board read whose arithmetic had been wrong since Chapter 193, a correction in the wrong character's mouth, and a refusal ordinal that collided between 198 and 200) and five process or state matters, of which one is that the quality gate is not met by a repair pass. The four prose defects are closed in the chapters and in six state files; no chapter was rewritten, no beat was moved and no date was changed. The first half of the file is still a self-review and nothing may describe the whole file as a verdict.** |

**Note the delivered batch sizes, because `outline/volume-04.md`'s batch map does not use them.** The outline's map runs batches of ten — it places 181–192 in Batch 0004 and 193–200 in Batch 0005 — while delivery has run batches of five, so the outline's batch numbers and the delivered batch numbers do not refer to the same things. Read chapter ranges, not batch numbers, when checking anything in this table.

**A repair pass is not an independent review.** When a reviewer's findings are applied by the author of the prose, the resulting record is still the author's, and it says so. What a repair pass can honestly claim is narrower and worth stating plainly: named, checkable defects were corrected, and the corrections are visible in a diff. What it cannot claim is that the batch has been independently reviewed, and no amount of thoroughness inside the authoring session changes that.

**The failure this register exists to prevent, recorded because it happened:** a self-review sat in this directory under a filename and a heading that a reader would take for a finding, seven measurable claims in it were false or overstated, and it took an outside review to find them. The claim that shook it loose was a *method* that could not produce the answer it reported — a duplication pass built on paragraph prefixes, which cannot see a repeat buried inside two longer paragraphs, reporting a clean sheet while a twenty-word line sat verbatim in Chapter 188. **A measure that reports what its instrument is built to find, and nothing else, is not a measure.**
