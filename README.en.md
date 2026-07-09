*✍️ 100% human, written by myself, without AI.*
*🇫🇷 Vous cherchez la version française ? [Cliquez ici](./README.md)*

# 👋 Hi there!

I'm a software/web engineer and architect, focused on using **pure functional programming** to unlock **extreme real-world constraints**. Currently, I'm looking for an ambitious project to found or boost, in which I believe 100%.

Scalability, reliability, maintainability. It is on this alloy that my attention has **polarized** over the past few years, designing systems that maximize these three properties **without sacrifice**. Whether it means making modern state-of-the-art ecosystems secure and truly scalable, targeting legacy servers without sacrificing modern safety, or pushing relational databases to their physical limits: my goal is to respond very quickly to millions of requests per day (for customers as a whole), without bugs (for an isolated customer), with ease and velocity (for the technical team).

### 🔬 Current focus and research

* 🧩 **Runtime agnosticism**: I design pure business logic decoupled from specific execution environments. My current work is bringing strict FP to [**places**](https://github.com/0x000000000000000000001/phpurs) where it is not often found, leveraging massive existing ecosystems without sacrificing advanced type safety. I am deeply convinced that the era of religious battles between programming languages is **over**. It is time to take advantage of each language's strengths (e.g. Erlang for fault-tolerance, PHP for ubiquitous deployment, Node.js for async I/O, C/C++/Rust/Chez Scheme for raw execution speed, etc.) by fostering intelligent dialogue between them. This is done through a language that is abstract enough to act as a universal layer, without suffering from the *"lowest common denominator"* syndrome (e.g. Haxe), and offering optimized/powerful FFI and compilation.

* ⚡ **Lock-free architectures**: I'm exploring interesting [**event sourcing patterns**](https://github.com/ricofritzsche/ccc-postgres-concurrency-proof/issues/1). I focus on pushing monolithic databases (like PostgreSQL) to FAANG-level scale (60k+ TPS) using custom paradigms like aggregateless DDD, *Context Collision Observers* (CCO) and optimistic batching. 

* 📐 **Pure FP and Category Theory**: Using mathematical rigor not only for the beauty of the theory itself (thanks [Milewski](https://bartoszmilewski.com) ❤️), but to solve notoriously hard engineering problems like concurrency, distributed state, cache invalidation, time machines (Time Travel Debugging), architecture symmetry, etc.

### 🔄 Technical shifts I am accustomed to:

**(Paradigm)**
* Ad-hoc constructs ➔ Formal foundations *(e.g. Lambda Calculus, Category Theory: Typeclasses, ADTs, Functors & Monads, Algebraic Effects, Polymorphic Variants, Type|Kind-Level Programming, Phantom Types...)*
* GoF design patterns ➔ Algebraic abstractions
* Imperative ➔ Declarative
* Statements ➔ Expressions
* Code as text ➔ Code as (irrefutable) mathematical proof trees *(i.e. Curry-Howard isomorphism)* 

**(Safety)**
* Implicit hell ➔ Explicit types, constraints & effects
* Primitive obsession ➔ Zero-cost abstractions
* Defensive programming ➔ MISU *(Make Illegal States Unrepresentable)*
* Runtime errors ➔ Compile-time safety *(Hindley-Milner, System F...)*
* Bug detection ➔ Bug prevention

**(Architecture)**
* Database-driven & framework-driven ➔ Domain-driven & context-centric (see [Rico Fritzsche's work](https://urlr.me/2pkmja))
* Horizontal layers ➔ Hexagonal & vertical layers
* Leaky abstractions ➔ Hermetic abstractions
* Human discipline ➔ Type-enforced architecture++ *(e.g. TypeScript ➔ PureScript)*
* Single-runtime language lock-in ➔ Runtime-agnostic language *(Browser, Node/V8, Erlang/BEAM, ...)* (more explanation [here](https://urlr.me/4cEkGH))

**(Data & performance)**
* CRUD ➔ High-performance Event Sourcing & CQRS (example [here](https://urlr.me/qSgyDM))
* Nested mutations ➔ Immutables & optics *(Lenses, Prisms...)*
* UI: 2-way data binding ➔ TEA *(The Elm Architecture)*
* Single-threaded ➔ Concurrent & parallel-threaded
* RAM-heavy (€€€) ➔ Disk-optimized (€)
* API & ops time in N ms ➔ ... in N/10 or N/100 ms

### 🧠 Philosophy: a healthy complexity transfer

I want to reassure you on one point: I am aware of the complexity of my descriptions. All this is not intended to complicate things for the sake of complicating them, but rather to accommodate, at the same level, the increased complexity that accompanies your growth. You have to see this as a complexity transfer: as the internal logic of the company becomes more complex (e.g. customer traffic, server fleet, internal teams...), it is a question of responding with **dense conceptual buffers** that capture this complexity, thus avoiding distorting your interfaces, those of developers, your internal organization, etc. I have a deeply ingrained conviction that a rich technical stack relieves the entire group. This is therefore less intended to intimidate than to offer you a credible vision of things, supported by **tangible elements**. In my view, good complexity is intentional, controlled complexity, as opposed to contingent and accidental complexity leaking all the way to the product itself, and felt by the customers.

*Current note: a certain number of these choices fit well with an AI-oriented corporate policy. From an agentic point of view, an AI is offered rails and guardrails (e.g. Hindley-Milner, System F...) which considerably reduce its stochastic search space.*

### 💬 Let's talk!

If this short manifesto intrigues you, feel free to contact me for a deeper exchange elsewhere, between humans!

On a technical level, I would be delighted to discuss: runtime agnosticism, Event Sourcing, PLT & compilers, FP, Category Theory, Postgres internals...

And/or on a general level, let's talk about your concrete projects!
