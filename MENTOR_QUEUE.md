# Mentor Continuation and Anti-Repeat Checklist

**Canonical status:** [LEARNING_STATE.json](LEARNING_STATE.json)  
**Roadmap:** [ROADMAP_12_BATCHES.md](ROADMAP_12_BATCHES.md)  
**User:** Continue the 12-batch standalone Java course only. The old 11-batch lesson and tracker section were deleted at the user's explicit request.

## Current situation (2026-10-04)

- [x] **Batch 01 — Java and the Development Environment:** Complete original [lesson archive](sessions/session-01/2026-mentor-batches/batch-01-exact.txt). User explicitly confirmed **Understood Batch 01** on 2026-10-04. **Do not repeat** the full JDK/JRE/JVM explanation as a new lesson.
- [x] **Batch 02 — Classes and Objects:** Full original [lesson archive](sessions/session-01/2026-mentor-batches/batch-02-exact.txt) written. Covers Employee class, fields, simple method, two distinct instances, `new Employee()`, null-reference failure and default instance-field values.
- [ ] **Batch 02 confirmed understood:** **NO.** Presented, awaiting user's exact confirmation.
- [ ] **Batch 03 — Constructors and Constructor Overloading:** Next only after user confirms Batch 02.
- [ ] Batch 04 — `this` and Java Memory.
- [ ] Batch 05 — Public Classes vs Public Constructors.
- [ ] Batch 06 — Access Modifiers.
- [ ] Batch 07 — Four OOP Pillars.
- [ ] Batch 08 — Abstract Classes and Inheritance.
- [ ] Batch 09 — Multilevel Inheritance / Concrete Classes.
- [ ] Batch 10 — Constructors in Abstract Classes.
- [ ] Batch 11 — Multiple Inheritance / Diamond Problem.
- [ ] Batch 12 — Final OOP Interview Challenge.

## Exact next instruction

**WAIT for the user's "Understood Batch 02".** Then tick Batch 02, update `LEARNING_STATE.json` and `TRACKER.md`, and write **Batch 03 — Constructors and Constructor Overloading**, based on transcript 08:16–13:28. Do not start by re-explaining classes and objects. Focus on *why initialization at creation time matters*, the rules for implicit no-arg constructors, user-defined parameterized constructors and overloading. Save the original Batch 03 response exactly as authored, including code, diagrams and Test Your Understanding.

## Never repeat / accuracy record

- **Already understood:** IntelliJ vs JDK, javac vs JVM, Java source to bytecode, platform independence, Java 21 orientation (Batch 01).
- **Already introduced but not confirmed:** Employee as blueprint, object as individual instance, field/method distinction, object references and `new`, independent instance values, null-reference failure (Batch 02). An intentionally limited constructor teaser appears in Batch 02; explain constructors thoroughly in Batch 03 as new learning, not a repeat.
- **Save for later:** `this` and heap/stack (Batch 04), public/private/protected/default access (Batches 05–06), encapsulation (Batch 07), abstract class details (Batches 08–10), multiple inheritance (Batch 11).
- **Technical corrections from original transcript:** Java does NOT auto-create an implicit no-arg constructor after you declare another constructor. Abstract classes can have abstract and implemented methods and constructors. Top-level classes cannot be private or protected; inner classes have different rules.
- **Source preservation:** Full original assistant lesson files are immutable. Chat-specific interactive components live as unexecuted source text in `.txt` on GitHub. Never rewrite, summarize, or silently overwrite an original batch.
- **No other projects:** Keep this standalone course separate from other GitHub repositories and experience trackers.

## Mandatory procedure for every new branch

1. Fetch `LEARNING_STATE.json`, this file, `TRACKER.md`, the 12-batch roadmap and last original `.txt` archive from [Java-Learning-Theory](https://github.com/sabareeshrao/Java-Learning-Theory).
2. Confirm whether the active batch is **presented** or **understood**. Only the user's explicit "Understood" changes the latter.
3. Continue at the active batch without reteaching earlier material, unless the student specifically asks for a review.
4. Preserve each new batch's **full exact response** in a new numbered archive; keep progress metadata separate. If a rewrite is requested, save a new revision rather than overwriting the original.
5. Upon explicit confirmation: commit the completion status, update tracker and mentor queue, then write the next batch in the same turn. Keep the five-year-mentor / new-graduate-student tone, problem → question → why → explanation → code → failure → interview answer → memory trick → Test Your Understanding.
6. Original lecture transcript excerpt under `sessions/session-01/source/batch-01-verbatim.txt` is retained as user-supplied reference, **not** an obsolete 11-batch lesson; the actual obsolete shorter authored lesson was deleted.

**Continuation phrase:** "Continue Java Learning Theory from GitHub. Read LEARNING_STATE.json and MENTOR_QUEUE.md. Resume at the active 12-batch lesson, keep exact originals unchanged, and do not repeat completed batches."
