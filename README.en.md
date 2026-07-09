*✍️ 100% human, written by myself, without AI.*
*🇫🇷 Vous cherchez la version française ? [Cliquez ici](./README.md)*

# 👋 Hi there!

I'm a software engineer and architect focused on using **pure functional programming** to unlock **extreme real-world constraints**. Currently, I'm looking for an ambitious project to found or boost, in which I believe 100%.

Scalability, Reliability, Maintainability. It is on this alloy that my attention has polarized over the past few years, designing systems that maximize these three properties without sacrifice. Whether that means making modern state-of-the-art ecosystems secure and truly scalable, or bypassing them to target legacy servers without sacrificing modern safety, or pushing relational databases to their physical limits: my goal is to respond very quickly to millions of requests per day (for customers as a whole), without bugs (for an isolated customer), with ease and velocity (for the technical team).

### 🔬 Current focus and research

* 🧩 **Runtime agnosticism**: I design pure business logic decoupled from specific execution environments. My current work is bringing strict FP to [**places**](https://github.com/0x000000000000000000001/phpurs) where it is not often found, leveraging massive existing ecosystems without sacrificing advanced type safety. I am deeply convinced that the era of religious battles between programming languages is **over**. It is time to take advantage of each language's strengths (e.g. Erlang for fault-tolerance, PHP for ubiquitous deployment, Node.js for async I/O, C/C++/Rust/Chez Scheme for raw execution speed, etc.) by fostering intelligent dialogue between them. This is done through a language that is abstract enough to act as a universal layer, without suffering from the *"lowest common denominator"* syndrome (e.g. Haxe), and offering optimized/powerful FFI and compilation.

* ⚡ **Lock-free architectures**: I'm exploring interesting [**event sourcing patterns**](https://github.com/ricofritzsche/ccc-postgres-concurrency-proof/issues/1). I focus on pushing monolithic databases (like PostgreSQL) to FAANG-level scale (60k+ TPS) using custom paradigms like Aggregateless DDD, *Context Collision Observers* (CCO) and optimistic batching. 

* 📐 **Pure FP and Category Theory**: Using mathematical rigor not only for the beauty of the theory itself (thanks [Milewski](https://bartoszmilewski.com) ❤️), but to solve notoriously hard engineering problems like concurrency, distributed state, cache invalidation, time machines (Time Travel Debugging), architecture symmetry, etc.

### 🔄 Technical shifts I am accustomed to:

**(Paradigm)**
* Ad-hoc Constructs ➔ Formal Foundations* *(e.g. Category Theory, Lambda Calculus...)*
* GoF Design Patterns ➔ Algebraic Abstractions*
* Imperative ➔ Declarative
* Statements ➔ Expressions
* Code as Text ➔ Code as (irrefutable) Mathematical Proof Trees *(i.e. Curry-Howard isomorphism)*
*\* Examples: Typeclasses, ADTs, Functors & Monads, Algebraic Effects, Polymorphic Variants, Type|Kind-Level Programming, Phantom Types...* 

**(Safety)**
* Implicit Hell ➔ Explicit Types, Constraints & Effects
* Primitive Obsession ➔ Zero-Cost Abstractions
* Defensive Programming ➔ MISU *(Make Illegal States Unrepresentable)*
* Runtime Errors ➔ Compile-Time Safety *(Hindley-Milner, System F...)*
* Bug Detection ➔ Bug Prevention

**(Architecture)**
* Database-Driven & Framework-Driven ➔ Domain-Driven & Context-Centric*
* Horizontal Layers ➔ Hexagonal & Vertical Layers
* Leaky Abstractions ➔ Hermetic Abstractions
* Human Discipline ➔ Type-Enforced Architecture++ *(e.g. TypeScript ➔ PureScript)*
* Single-Runtime Language Lock-in ➔ Runtime-Agnostic Language *(Browser, Node/V8, Erlang/BEAM, ...)* **
*\* [See Rico Fritzsche's work](https://urlr.me/2pkmja)*
*\*\* [More explanation here](https://urlr.me/4cEkGH)*

**(Data & Performance)**
* CRUD ➔ High-Performance Event Sourcing & CQRS*
* Nested Mutations ➔ Immutables & Optics *(Lenses, Prisms...)*
* UI: 2-Way Data Binding ➔ TEA *(The Elm Architecture)*
* Single-Threaded ➔ Concurrent & Parallel-Threaded
* RAM-heavy (€€€) ➔ Disk-optimized (€)
* API & Ops Time in N ms ➔ ... in N/10 or N/100 ms
*\* [Example here](https://urlr.me/qSgyDM)*

---

### 🧠 Philosophy (A healthy complexity transfer)

I want to reassure you on one point: I am aware of the complexity of my descriptions. All this is not intended to complicate things for the sake of complicating them, but rather to accommodate, at the same level, the increased complexity that accompanies your growth. You have to see this as a complexity transfer: as the internal logic of the company becomes more complex (e.g. customer traffic, server fleet, internal teams...), it is a question of responding with dense conceptual buffers that capture this complexity, thus avoiding distorting your interfaces, those of developers, your internal organization, etc. I have a deeply ingrained conviction that a rich technical stack relieves the entire group. This is therefore less intended to intimidate than to offer you a credible vision of things, supported by tangible elements.

*Current note: a certain number of these choices fit well with an AI-oriented corporate policy. From an agentic point of view, an AI is offered rails and guardrails (e.g. Hindley-Milner, System F...) which considerably reduce its stochastic search space.*

### 💬 Let's talk about:
Runtime agnosticism, Event Sourcing, PLT & Compilers, FP, Category Theory, Postgres internals, and building majestic monoliths for your real-world projects!

If this short manifesto intrigues you, feel free to contact me for a deeper exchange elsewhere, between humans!
