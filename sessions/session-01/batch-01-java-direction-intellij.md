# Session 1 — Batch 01
## Java Learning Direction + IntelliJ Setup

**Transcript window:** 00:00–04:06

**Characters**
- 🐯 **Mentor** — Java developer with 10 years of industry experience
- 🐼 **Student** — recent graduate; Java was one subject in college, but no industry experience yet

> **Source rule:** The original transcript for this batch is preserved separately in source/batch-01-verbatim.txt. This file is the learning/conversation layer and does not replace the original words.

---

🐼 **Student:** Before we start, I wanted to clarify the direction. I was told there isn't much value in spending time learning old JDK versions first, and that interviews will mostly focus on modern Java. So can we briefly cover the JDK side and mainly focus on Java 21?

🐯 **Mentor:** Yes, we can make Java 21 the modern target. But I don't want you to confuse **learning a modern Java version** with **skipping Java fundamentals**.

Before features such as virtual threads make sense, you still need to be comfortable with the things the language is built on:

~~~text
Core Java fundamentals
        ↓
Classes and objects
        ↓
Collections
        ↓
Exception handling
        ↓
Polymorphism and other OOP concepts
        ↓
Modern Java features
        ↓
Spring Boot / application development
~~~

Java 21 gives us newer capabilities, and we'll get to those. But the basic Java concepts are still the foundation underneath them.

🐼 **Student:** So we aren't going to study every JDK version one by one?

🐯 **Mentor:** No. That wouldn't be a useful way to spend your learning time here.

The better approach for you is:

~~~text
Understand the language properly
          +
Know the modern Java features that matter
          =
Useful Java knowledge
~~~

You should know what you're writing and why you're writing it. Once that foundation is there, newer features are much easier to understand.

🐼 **Student:** I originally thought we were going directly into a Spring Boot application.

🐯 **Mentor:** We will get there, but starting with Core Java is the right move.

Think about it from a real project point of view. Spring Boot is still Java. Your controllers, services, DTOs, exceptions, collections, objects, constructors, inheritance—all of that depends on Java fundamentals.

If we jump directly into Spring Boot, you might learn to type annotations such as @RestController, @Service, and @Autowired, but you may not understand what the Java code around those annotations is actually doing.

I would rather have you reach Spring Boot and think:

> “Okay, this is still Java. Spring is giving me additional framework behavior.”

instead of thinking:

> “Spring Boot is some completely different thing.”

🐼 **Student:** That makes sense. In college I learned Java as a subject, so I've seen concepts like OOP, exceptions and collections, but I haven't really used them in a job.

🐯 **Mentor:** Exactly. That's the gap we're going to close.

I don't need to treat you as though you've never seen Java before. But I also won't assume that knowing the definition from college means you've seen how the concept behaves in a real codebase.

So when we cover something basic, the question won't only be:

> “What is this?”

We'll also keep asking:

> “Why would a developer need this?”

and later:

> “Where does this appear in an actual application?”

---

## Choosing the IDE

🐯 **Mentor:** Now we need an IDE so we can actually write and test the code.

For these sessions we'll use **IntelliJ IDEA**.

🐼 **Student:** I've mostly worked with VS Code and Eclipse. I know what IntelliJ looks like because I've seen it in Java tutorials, but I haven't used it as much.

🐯 **Mentor:** That's completely fine.

VS Code can be used for Java too, and Eclipse is also familiar to a lot of Java developers. But IntelliJ is a very common environment for Java development, especially once we move toward Spring Boot.

For the learning sessions, using the same IDE also removes unnecessary friction.

Instead of us constantly translating:

~~~text
"Where is this option in Eclipse?"
"Where is the equivalent command in VS Code?"
"Why does your project view look different?"
~~~

we can stay focused on Java.

🐼 **Student:** I already activated an IntelliJ student account, so I have access to it.

🐯 **Mentor:** Good. IntelliJ basically gives you two editions to be aware of here:

~~~text
IntelliJ IDEA
│
├── Community Edition
│   └── Free to use
│
└── Ultimate Edition
    └── Licensed / paid edition
~~~

For the Core Java work we're doing right now, **Community Edition is enough for testing and learning**.

So don't make the tool itself the problem.

At this stage, what matters is:

~~~text
Can you create the project?
Can you create a Java class?
Can you run the code?
Can you see compiler errors?
Can you inspect the output?
~~~

If yes, we have what we need.

🐼 **Student:** So for now the IDE is just our working environment. The real focus is getting the Java foundation right.

🐯 **Mentor:** Exactly.

And this is an important mindset when you're new to industry: don't confuse **knowing a tool** with **knowing the underlying technology**.

IntelliJ helps you write Java.

It does not replace understanding Java.

---

## Batch 01 Mental Model

~~~text
                    JAVA LEARNING PATH

             ┌───────────────────────┐
             │ Core Java Fundamentals│
             └───────────┬───────────┘
                         │
                         ▼
       ┌──────────────────────────────────┐
       │ Collections / Exceptions / OOP   │
       └─────────────────┬────────────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Modern Java / JDK21 │
              │ e.g. virtual threads│
              └──────────┬──────────┘
                         │
                         ▼
                ┌────────────────┐
                │  Spring Boot   │
                │ Applications   │
                └────────────────┘

Working environment for the course:
             IntelliJ IDEA
~~~

---

## What the Student Should Leave This Batch Understanding

🐼 **Student:** Let me make sure I have the main idea.

We're going to focus on modern Java, including Java 21 features, but we're not jumping over Core Java to get there.

We first make sure I understand the fundamental language concepts, then modern features will make more sense, and after that the same Java knowledge carries into Spring Boot.

And for our development environment we'll mainly use IntelliJ, with Community Edition being enough for the basic work.

🐯 **Mentor:** Correct.

That's enough for this batch.

The next thing we need is the first real OOP building block.

We're going to move from:

~~~text
"What should I learn?"
~~~

to:

~~~text
"What exactly is a class?"
"What is an object?"
"Why do we create constructors?"
"What's actually happening when I use new?"
~~~

That is where **Batch 02** starts.

---

**End of Session 1 — Batch 01**

**Next:** Batch 02 — Class, Object & Constructor Fundamentals
