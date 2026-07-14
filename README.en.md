*🇫🇷 Vous cherchez la version française ? [Cliquez ici](./README.md)*

*✍️ 100% human, written by myself, without AI. I think what I write.*

*💻 I'm currently open to work (cofounding, permanent contract, freelance...)*

# 👋 Hi there!

I am a software/web engineer/architect focused on using **pure functional programming** (FP) to overcome **extreme real-world constraints**, and **express business logic** with **high accuracy**. 

I initially gained experience through the lens of object-oriented programming (OOP), with common languages like C/C++, PHP, TypeScript (and their frameworks)... but I’ve always kept one foot in FP as well. Over the years, I eventually encountered a number of [fundamental limitations](https://www.youtube.com/watch?v=wo84LFzx5nI) in OOP, beyond my control. That forced me to turn the page, and set aside some of my knowledge, in order to move toward what may be one of the deepest [tectonic shifts](https://youtu.be/QyJZzq0v7Z4?t=2191) in today’s industry (OOP → hybrid FP style → FP), still ongoing (e.g. [there](https://github.com/IBM/fp-go) in IBM, [there](https://github.com/gcanti/fp-ts) thanks to Unspash, strong [influences](https://doc.rust-lang.org/stable/book/ch13-00-functional-features.html?utm_source=chatgpt.com) on Rust in Mozilla, ...). 

I also believe, like [Milewski](https://www.youtube.com/watch?v=XZl5DglVTCs), that the future of programming lies in the ability to **express** mathematized ideas (invariants, effects, laws, etc.) using languages rooted in modern theories (e.g., Category Theory, HoTT, etc.). As I wrote [on my blog](https://dev.to/0x1/zero-developers-in-2026-musk-is-right-but-wrong-1nm2), code is increasingly being handled by AI, but the definition of programming is changing: it is becoming more mathematical, and remains human: it's no longer a matter of telling the machine _how_ to do something, but _what_ to do (and that is still very technical).

Scalability, Reliability, Maintainability. It is on this alloy that my attention has **polarized** over the past few years, designing systems that maximize these three properties **without sacrifice**. Whether it means making modern state-of-the-art ecosystems secure and truly scalable, targeting legacy servers without sacrificing modern safety, or pushing relational databases to their physical limits: my work is to respond very quickly to millions of requests per day (for customers as a whole), without bugs (for an isolated customer), with ease and velocity (for the technical team).

That’s the big picture and the overall trajectory!

Right now, I'm looking for an ambitious project to **start from scratch** or **boost**, one that I believe in 100%.

### 🔬 Current focus and research

* 🧩 **Runtime agnosticism**: I design pure business logic decoupled from specific execution environments. My current work is bringing strict FP to [**places**](https://github.com/0x000000000000000000001/phpurs) where it is not often found, leveraging massive existing ecosystems without sacrificing advanced type safety. I am deeply convinced that the era of religious battles between programming languages is **over**. It is time to take advantage of each language's strengths (e.g. Erlang for fault-tolerance, PHP for ubiquitous deployment, Node.js for async I/O, C/C++/Rust/Chez Scheme for raw execution speed, etc.) by fostering intelligent dialogue between them. This is done through a language that is abstract enough to act as a universal layer, without suffering from the *"lowest common denominator"* syndrome (e.g. Haxe), and offering optimized/powerful FFI and compilation. I discuss this topic in more detail [in this article](https://dev.to/0x1/the-ultimate-polymorphism-purescript-as-a-universal-language-5gdi), and I've created a publicly [testable proof](https://github.com/0x000000000000000000001/b8x.pub#-runtime-agnostic-in-the-real-world) of it, even though a number of engineers familiar with the subject already know this (since they've also released their own public compilers).

* ⚡ **Lock-free architectures**: I'm exploring interesting event sourcing patterns ([POC](https://github.com/0x000000000000000000001/ccc-postgres-concurrency-proof/tree/feat/cco), originally discussed [here](https://github.com/ricofritzsche/ccc-postgres-concurrency-proof/issues/1), also implemented in a [real-world project](https://github.com/0x000000000000000000001/b8x.pub#%EF%B8%8F-event-sourcing-architecture-postgresql-native)). I focus on pushing monolithic databases (like PostgreSQL) to FAANG-level scale (60k+ TPS) using custom paradigms like aggregateless DDD, *Context Collision Observers* (CCO) and optimistic batching. 

* 📐 **Pure FP and Category Theory**: Using mathematical rigor not only for the beauty of the theory itself (thanks [Milewski](https://bartoszmilewski.com) ❤️), but to solve notoriously hard engineering problems like concurrency, distributed state, cache invalidation, time machines (Time Travel Debugging), architecture symmetry, etc.

### 🔄 Technical shifts I am accustomed to:

<table>
  <thead>
    <tr>
      <th>Theme</th>
      <th>Before</th>
      <th>After</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5"><b>Paradigm</b></td>
      <td>Ad-hoc Constructs</td>
      <td>Formal Foundations <i>(e.g. Lambda Calculus, Category Theory: Typeclasses, ADTs, Functors & Monads, Algebraic Effects, Polymorphic Variants, Type|Kind-Level Programming, Phantom Types...)</i></td>
    </tr>
    <tr>
      <td>GoF Design Patterns</td>
      <td>Algebraic Abstractions</td>
    </tr>
    <tr>
      <td>Imperative</td>
      <td>Declarative</td>
    </tr>
    <tr>
      <td>Statements</td>
      <td>Expressions</td>
    </tr>
    <tr>
      <td>Code as Text</td>
      <td>Code as (irrefutable) Mathematical Proof Trees <i>(i.e. Curry-Howard isomorphism)</i></td>
    </tr>
    <tr>
      <td rowspan="5"><b>Safety</b></td>
      <td>Implicit Hell</td>
      <td>Explicit Types, Constraints & Effects</td>
    </tr>
    <tr>
      <td>Primitive Obsession</td>
      <td>Zero-Cost Abstractions</td>
    </tr>
    <tr>
      <td>Defensive Programming</td>
      <td>MISU <i>(Make Illegal States Unrepresentable)</i></td>
    </tr>
    <tr>
      <td>Runtime Errors</td>
      <td>Compile-Time Safety <i>(Hindley-Milner, System F...)</i></td>
    </tr>
    <tr>
      <td>Bug Detection</td>
      <td>Bug Prevention</td>
    </tr>
    <tr>
      <td rowspan="5"><b>Architecture</b></td>
      <td>Database-Driven & Framework-Driven</td>
      <td>Domain-Driven & Context-Centric (see <a href="https://urlr.me/2pkmja">Rico Fritzsche's work</a>)</td>
    </tr>
    <tr>
      <td>Horizontal Layers</td>
      <td>Hexagonal & Vertical Layers</td>
    </tr>
    <tr>
      <td>Leaky Abstractions</td>
      <td>Hermetic Abstractions</td>
    </tr>
    <tr>
      <td>Human Discipline</td>
      <td>Type-Enforced Architecture++ <i>(e.g. TypeScript ➔ PureScript)</i></td>
    </tr>
    <tr>
      <td>Single-Runtime Language Lock-in</td>
      <td>Runtime-Agnostic Language <i>(Browser, Node/V8, Erlang/BEAM, ...)</i> (more explanation <a href="https://urlr.me/4cEkGH">here</a>)</td>
    </tr>
    <tr>
      <td rowspan="6"><b>Data & Performance</b></td>
      <td>CRUD</td>
      <td>High-Performance Event Sourcing & CQRS (example <a href="https://urlr.me/qSgyDM">here</a>)</td>
    </tr>
    <tr>
      <td>Nested Mutations</td>
      <td>Immutables & Optics <i>(Lenses, Prisms...)</i></td>
    </tr>
    <tr>
      <td>UI: 2-Way Data Binding</td>
      <td>TEA <i>(The Elm Architecture)</i></td>
    </tr>
    <tr>
      <td>Single-Threaded</td>
      <td>Concurrent & Parallel-Threaded</td>
    </tr>
    <tr>
      <td>RAM-heavy (€€€)</td>
      <td>Disk-optimized (€)</td>
    </tr>
    <tr>
      <td>API & Ops Time in N ms</td>
      <td>... in N/10 or N/100 ms</td>
    </tr>
  </tbody>
</table>

### 🧠 Philosophy: a healthy complexity transfer

I want to reassure you on one point: I am aware of the complexity of my descriptions. All this is not intended to complicate things for the sake of complicating them, but rather to accommodate, at the same level, the increased complexity that accompanies your growth. You have to see this as a complexity **transfer**: as the internal logic of the company becomes more complex (e.g. customer traffic, server fleet, internal teams...), it is a question of responding with **dense conceptual buffers** that **capture** this complexity, thus avoiding distorting your interfaces, those of developers, your internal organization, etc. I have a deeply ingrained conviction that a rich technical stack relieves the entire group. This is therefore less intended to intimidate than to offer you a credible vision of things, supported by **tangible elements**. In my view, good complexity is intentional, controlled complexity, as opposed to contingent and accidental complexity leaking all the way to the product itself, and felt by the customers and/or the developers.

*Current note: a certain number of these choices fit well with an AI-oriented corporate policy. From an agentic point of view, an AI is offered rails and guardrails (e.g. Hindley-Milner, System F...) which considerably reduce its stochastic search space.*

### 💬 Let's talk!

If this short manifesto intrigues you, feel free to contact me for a deeper exchange elsewhere, between humans!

On a technical level, I would be delighted to discuss: runtime agnosticism, Event Sourcing, PLT & compilers, FP, Category Theory, Postgres internals...

And/or on a general level, let's talk about your concrete projects!
