# Java Core — Lecture 01 — 12-Batch Roadmap

**Origin:** User-supplied 61-minute classroom transcript, 00:00–1:01:26.  
**Course:** Independent, standalone mentor–student learning track; **not** the user's geospatial experience project or any other GitHub Tracker.  
**Learning voice:** Mentor with five years of Java experience; student just finished college Java and has zero industry experience.  
**Teaching principle:** Explain the practical problem first, then introduce the concept, code, failure case, interview-ready answer, one-line memory trick, and **Test Your Understanding**.  
**Source preservation:** Do not edit or replace previously authored original batch text. Keep exact source (including formatting and chat-specific markup) in `sessions/session-01/2026-mentor-batches/`.

| Batch | Transcript window | Title | Core interview question | Initial state |
|---|---|---|---|---|
| **01** | 00:00–04:05 | Understanding Java and the Development Environment | Why do we need a JDK and an IDE? Understand JDK/JRE/JVM, compilation, Java 21 and IntelliJ. | **✅ Understood — 2026-10-04** |
| 02 | 04:06–08:15 | Classes and Objects | What exactly happens when we create an Employee object? Class, fields, methods, objects, `new`. | **✅ Understood — 2026-10-05** |
| 03 | 08:16–13:28 | Constructors and Constructor Overloading | Why does Java need constructors and can one class have multiple constructors? Implicit no-arg constructor rules. | **✅ Understood — 2026-10-05** |
| 04 | 13:29–17:37 | The `this` Keyword and Java Memory | Which object are we modifying? `this`, references, stack and heap, per-object state. | **✅ Understood — 2026-10-05** |
| 05 | 17:38–24:55 | Public Classes vs Public Constructors | Why can a class be visible while its constructor is inaccessible? Package boundaries. | **✅ Understood — 2026-10-05** |
| 06 | 24:56–34:37 | All Four Access Modifiers | What do public, private, protected and package-private permit? | **✅ Understood — 2026-10-05** |
| 07 | 34:38–37:22 | The Four Pillars of OOP | Why encapsulation, inheritance, abstraction and polymorphism? | **🟠 Presented — awaiting understanding** |
| 08 | 37:23–41:56 | Abstract Classes and Inheritance | Why does a Vehicle declare a method without implementation? | Queued |
| 09 | 41:57–51:35 | Multilevel Inheritance and Concrete Classes | How do Vehicle, Car and BMW inherit and implement methods? | Queued |
| 10 | 51:36–55:48 | Constructors in Abstract Classes | Why can an abstract class have a constructor even though it cannot be instantiated directly? | Queued |
| 11 | 55:49–59:00 | Multiple Inheritance and the Diamond Problem | Why can't a Java class extend two classes? How can interfaces help? | Queued |
| 12 | 59:00–1:01:26 and recap | Java OOP Interview Challenge | Put everything together; cover the lecturer's homework and check understanding. | Queued |

## Important technical accuracy notes

The transcript is unedited historical source, not necessarily technically correct. In the independently authored lessons explain accurately that:

- An implicit no-argument constructor is created **only when no constructor is explicitly declared**.
- Abstract classes may contain fully implemented methods, abstract methods, and constructors.
- `this` refers to the current object in an instance context.
- Classes cannot extend multiple classes; interfaces permit multiple inheritance of type, with defined resolution rules for default methods.
- Top-level classes cannot be declared private or protected; nested classes have different rules.
- Private constructors are legal and useful for controlled instantiation and utility classes.
- A class with an explicit constructor does not automatically get a separate implicit no-arg constructor.

## Continuation

Read [the current course state](LEARNING_STATE.json) and [mentor checklist](MENTOR_QUEUE.md) before generating the next batch. **Follow only this 12-batch roadmap. The obsolete 11-batch course lesson and tracker have been removed at the user's request.**

Current exact Batch 01: [full original, unrewritten](sessions/session-01/2026-mentor-batches/batch-01-exact.txt).

**Counts:** 7 / 12 batches authored; **6 / 12 explicitly understood** (Batches 01–06). Batch 07 is presented and awaiting confirmation. This is not the 1,000-question experience course.
