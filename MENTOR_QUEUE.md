# Mentor Continuation and Anti-Repeat Checklist

**FIRST FILE TO CHECK FOR THIS COURSE:** [LEARNING_STATE.json](LEARNING_STATE.json), then this file, then the relevant full exact source and [ROADMAP_12_BATCHES.md](ROADMAP_12_BATCHES.md).

## Current state / single next action

- [x] **Batch 01 authored and archived without rewriting** — [exact original response](sessions/session-01/2026-mentor-batches/batch-01-exact.txt). Topics: IDE vs JDK, `javac`, .java/.class and bytecode, JVM, cross-platform Java, JDK/JRE/JVM, Java 21, IntelliJ project setup, terminal compilation, unsupported class-version failure.
- [ ] **Batch 01 explicitly confirmed understood by user** — **NOT YET CONFIRMED IN THIS CHAT.** The old `TRACKER.md` has an earlier, different 11-batch plan with Batch 01 shown complete; that must not automatically count toward this track.
- [ ] **Batch 02 written.** Do not write it until the user confirms understanding of Batch 01 or explicitly requests Batch 02 as a detour. Batch 02 is **Classes and Objects**, following the supplied transcript (04:06–08:15), in the same detailed mentor/student format.
- [ ] Batch 03 — Constructors and Constructor Overloading.
- [ ] Batch 04 — `this` and Memory.
- [ ] Batch 05 — Public Classes vs Public Constructors.
- [ ] Batch 06 — Four Access Modifiers.
- [ ] Batch 07 — Four OOP Pillars.
- [ ] Batch 08 — Abstract Classes and Inheritance.
- [ ] Batch 09 — Multilevel Inheritance and Concrete Classes.
- [ ] Batch 10 — Constructors in Abstract Classes.
- [ ] Batch 11 — Multiple Inheritance and Diamond Problem.
- [ ] Batch 12 — OOP Interview Challenge.

## Before starting a new batch

1. Fetch [LEARNING_STATE.json](LEARNING_STATE.json), this checklist, [ROADMAP_12_BATCHES.md](ROADMAP_12_BATCHES.md), and the latest relevant exact lesson.
2. Check `activeBatch`, `presentedBatchIds` and `confirmedUnderstoodBatchIds`; **presented ≠ understood**.
3. Do not repeat an already-understood topic as a fresh batch. Brief references for prerequisites are fine; new material should come from the next batch's roadmap.
4. **Style contract:** Mentor = 5 years of practical Java experience, Student = college Java only. Relatable scenario → real problem → natural questions → introduce concept → brief illustrative code → failure case → interview answer → memory chain → 3-question Test Your Understanding. IntelliJ IDEA only, Java 21 where appropriate. No geospatial project or unrelated previous Tracker material.
5. Preserve the original user-visible authored batch **character-for-character**, including code and DIL UI source. Do not substitute a summary or rewritten version. A GitHub `.txt` source is for fidelity, not for running embedded chat UI.
6. Never rewrite an old exact archive. If the user requests a new revision, save it as a **new version** beside the original and explicitly show which one is current.
7. When the user says **"Understood"**, update `LEARNING_STATE.json`, this checklist, and the main tracker; then **write the next batch in that same turn**, using the original format. Save the new batch's complete original text either when authored, flagged as presented/awaiting understanding, or when the user confirms, but never assert confirmation early.
8. Preserve existing `sessions/session-01/batch-01-java-direction-intellij.md`, `sessions/session-01/source/`, and the original 11-batch history; do not confuse them with the new 12-batch track.

## Continuation phrase for branches

> "Continue the standalone Java Learning Theory course from GitHub `sabareeshrao/Java-Learning-Theory`. Read `LEARNING_STATE.json` and `MENTOR_QUEUE.md` first. Preserve every full batch verbatim. Resume at the active batch; don't repeat the completed batches."

**Next action now:** User has not yet confirmed Batch 01; invite them to answer the understanding test or say "Understood". On confirmation, commit the completed status and write **Batch 02 — Classes and Objects**.
