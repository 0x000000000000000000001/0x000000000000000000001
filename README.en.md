*🇫🇷 Vous cherchez la version française ? [Cliquez ici](./README.md)*

*✍️ 100% human, written by myself, without AI. I mean what I write.*

*💻 I am currently open to business offers (co-founding, permanent contract, freelance...)*

---

# 👋 Hello hello!

I am a software/web engineer and architect, focused on using **pure functional programming** (FP) to overcome **real-world constraints**, **express a business domain** with a **high degree of precision**, and design systems that structure the **search space** enough so that both humans and AIs naturally converge toward the right solutions. Put like this, it might legitimately sound like mere magic words or broad generalizations, but through this profile, I aim to show why and how.

I first gained experience through the lens of object-oriented programming (OOP), with mainstream languages like C/C++, PHP, TypeScript (and their frameworks: Symfony, Next, Nest, etc.)... but I always kept a hand in FP in parallel. Over the years, I ended up hitting a number of [fundamental limits](https://www.youtube.com/watch?v=wo84LFzx5nI) in OOP, beyond my control. They pushed me to turn the page, and to sacrifice part of my knowledge, in order to project myself toward one of the deepest [tectonic shifts](https://youtu.be/QyJZzq0v7Z4?t=2191) in the current industry (OOP → hybrid FP style → FP), which is still underway (e.g., [here](https://github.com/IBM/fp-go) at IBM, [there](https://github.com/gcanti/fp-ts) thanks to Unsplash, the strong [influences](https://doc.rust-lang.org/stable/book/ch13-00-functional-features.html?utm_source=chatgpt.com) on Rust at Mozilla with traits/impl/iterators/etc, ...). 

<br />
<img width="600" alt="images" src="https://github.com/user-attachments/assets/2246b10e-6d8d-449a-9307-d8b627263009" />
<br />
<br />

However, I am very aware of the technologies still at work today in the industry. This is actually what made me _Runtime-Agnostic_: what matters is no longer really this or that language, as such, but the **runtime** it brings with it, and that can be leveraged. In other words, I am **just as** interested in Go as I am in Rust, TypeScript/JavaScript, PHP, Roc, OCaml, Python... and it never ends! Every language has strengths and weaknesses: it is about activating strengths (e.g., resilience, speed, portability...) at the right time, in the right place. As **commonly** used languages, they have been tested and proven in the real world, and therefore serve as a perfect platform for executing programs. Hundreds of thousands of engineers have fixed bugs for them. Therefore, we can do the following: write code in another language, provided it is sufficiently abstract, in order to be completely free to express the most technical and scientific ideas possible, and then **compile** (i.e., transform the code) to all these languages. This gives us the best of both worlds: a language designed for its expressiveness, unlocking profound possibilities, coupled with the runtimes of field-tested, reliable, and efficient languages that execute the ideas expressed in the first.

My philosophy is therefore **mesomorphic, hybrid**, much like our modern screens (i.e., liquid crystals): **solid**, precise, structured, concise, and verifiable (by the machine) primary language and code; but **liquid**, flexible, and adaptable runtime, secondary code, and languages, taking into account the needs, history, and legacy of a company.  

Scalability, Reliability, Maintainability. This alloy is where my focus has been **polarized** for several years, designing systems that maximize these three properties **without compromise**. Whether it involves making modern ecosystems truly secure and scalable, targeting "legacy" servers without sacrificing modern safety, or pushing relational databases to their physical limits: my job is to respond very quickly to millions of requests per day (for customers as a whole), bug-free (for a single customer), with ease and velocity (for the technical team).

<br />
<img width="600" alt="strangler-fig-e1758297038747" src="https://github.com/user-attachments/assets/29ab8af8-a85a-480d-8b68-6e09aa5312b3" />
<br />
<br />

I add to this an important subject: the **technological pivot (Transpilation & Strangler Fig Pattern)**. By this, I mean the ability to orchestrate the complete migration of a company's code (from a "legacy" ecosystem/language to an ultra-high-performance native runtime like Rust or Go) with **no** risk of a _Big Bang_ rewrite. Like the natural strangler fig, which gradually wraps around an old tree until it entirely replaces it (without ever abruptly cutting it down), a well-designed FP language inserts itself into the existing codebase (via FFI: Foreign Function Interface). It thus mathematically isolates and secures the business logic in **islands**. Once the business code is sanitized, the decoupling is such that you only need to change the transpilation target to **switch** from one execution environment to another, in 10 seconds (this moment is particularly rewarding, here is a proof [at this location](https://github.com/0x000000000000000000001/b8x.pub#-runtime-agnostic-in-the-real-world): here, a project switches from one runtime/language (JS) to another (PHP), without changing a single line of code). We shift the project's complexity to the compilation architecture, allowing the company to radically change its performance class while continuing to deliver daily features. The exact same ones as usual, but: **faster**, much more **reliable**, and taking it much, much **further**. And of course, what was done once can be done again 10 years later, with another target language, but much faster: the insertion step having already been done, we will only have to rewrite a few FFIs, and then switch. Simply. This ensures the company a **natural update**, **permanently** aligned with new technologies and new performance standards, without sacrificing what it does best: its business, its own product.

I fundamentally believe, like [Milewski](https://www.youtube.com/watch?v=XZl5DglVTCs), that the future of programming lies in the ability to **express** mathematized ideas (invariants, effects, laws, etc.), with languages rooted in modern theories (e.g., Category Theory, HoTT, etc.). As I wrote [on my blog](https://dev.to/0x1/zero-developers-in-2026-musk-is-right-but-wrong-1nm2), coding is increasingly handled by AI, but programming is changing its definition, becoming mathematized, and remaining human: it's less and less about telling the machine _how_ to do things, but mainly _what_ to do (e.g., in the form of a decision tree), thereby favoring any programming paradigm moving in this direction.

That's it for the broad strokes and the overall trajectory!

Currently, I am looking for an ambitious project to **found** or **boost**, in which I can believe 100%.

---

### ⭐️ Why PureScript?

Why is PureScript so prevalent in my projects? 

Because it is a language directly **rooted** in the most **advanced** research (i.e., Haskell), with very high conceptual density, particularly powerful given the modern preference for **type safety** (i.e., what protects the code from a huge class of potential bugs), and also very pragmatic, as it is **open** to **legacy** (FFI). Therefore, it is a language capable of smartly **hybridizing** with what already exists, capable of working very closely with completely different languages. When you code in PureScript, you are actually also coding (if you want to) in Go, C++, Scheme, PHP, Python, Lua, JavaScript/TypeScript, Erlang, etc. And you don't do it in a scattered way; you do it in the **same codebase**. PureScript is a **central hub** leveraging each of these languages/ecosystems/runtimes, along with their strengths. Thus, it is not an ordinary language in the usual sense of the term. It is also a proxy language with very high added value (abstractions, design, underlying theory, conventions...). 

Its adoption curve looks like Haskell's: [organic](https://youtu.be/re96UgMk6GQ?t=728) (i.e., up-plateau-up-plateau...). In my opinion, this is the best possible scenario, because its evolvability is still free (not blocked by the risk of breaking massive existing systems), yet sufficiently influenced by real needs (significant adoption, replacing TypeScript, for example).

I've also had the opportunity to share my ideas on LinkedIn by engaging with peers. I believe one of the posts that best illustrates my conviction is this one:

<img width="419" height="878" alt="Screenshot 2026-08-29 at 12 31 41" src="https://github.com/user-attachments/assets/fe108470-2bdb-470a-bace-a07171f641c2" />

---

### 🔬 My current research axes

* 🧩 **Runtime agnosticism**: As explained above, I therefore design pure business logics, decoupled from specific execution environments, traditionally associated with mainstream industry languages. My current work involves bringing strict functional programming to places where its contribution is the most spectacular (e.g., like [here](https://github.com/0x000000000000000000001/phpurs) with PHP, [here](https://discourse.purescript.org/t/leveraging-a-blazing-fast-runtime-a-new-go-backend-for-purescript/5841) with Go, etc.), by leveraging massive existing ecosystems without sacrificing advanced type safety. I have the deep conviction that the era of religious wars between programming languages is **over**. It is time to take advantage of each language's strengths (e.g., Erlang for fault tolerance, PHP for ubiquitous deployment, Node.js for asynchronous I/O, C/C++/Rust/Chez Scheme for raw execution speed, etc.) by fostering an intelligent dialogue between them. This can notably be done via a language abstract enough to act as a universal layer, without suffering from the *"lowest common denominator"* syndrome (e.g., Haxe), and by offering an optimized/powerful FFI and compilation. I talk more at length about this topic [in this article](https://dev.to/0x1/the-ultimate-polymorphism-purescript-as-a-universal-language-5gdi), and I made a [publicly testable proof](https://github.com/0x000000000000000000001/b8x.pub#-runtime-agnostic-in-the-real-world) of it, [shared](https://discourse.purescript.org/t/leveraging-70-of-the-web-a-php-backend-for-purescript/5340) with a small number of engineers I work with, who are initiated into the subject. To make this agnosticism truly industrial, my work involves _Compiler Engineering_: beyond architecture, I design **compilers** to rebuild complete ecosystems (with native performance) like Go or PHP (via TCO, DCE, monomorphization, full porting of _Standard Libraries_...), while preserving the ability to use highly expressive languages true to pure thought (devoid of the machine's material contingencies). <br /><br /><img width="600" alt="Screenshot 2026-07-18 at 18 55 37" src="https://github.com/user-attachments/assets/3315e213-67d8-4dee-924f-9ef2fb90a49f" /><br /><br />

* ⚡ **"Lock-free" Architectures**: I explore interesting Event Sourcing patterns ([POC](https://github.com/0x000000000000000000001/ccc-postgres-concurrency-proof/tree/feat/cco), which I initially discussed [here](https://github.com/ricofritzsche/ccc-postgres-concurrency-proof/issues/1), also implemented in a [real project](https://github.com/0x000000000000000000001/b8x.pub#%EF%B8%8F-event-sourcing-architecture-postgresql-native)). I focus on the ability to push monolithic databases (like PostgreSQL) to a FAANG scale (60k+ TPS) using tailor-made paradigms like Aggregateless DDD, *Context Collision Observers* (CCO) and optimistic batching. <br /><br /><img width="600" alt="Screenshot 2026-07-18 at 18 42 49" src="https://github.com/user-attachments/assets/3218a122-d638-439e-9df1-50c978d46cb6" /><br /><br />

* 📐 **Pure FP and Category Theory**: I go through mathematical rigor, not only for the beauty of the theory itself (thank you [Milewski](https://bartoszmilewski.com) ❤️), but to solve notoriously difficult engineering problems: concurrency, distributed state, cache invalidation, "time machines" (Time Travel Debugging), architectural symmetry, etc. <br /><br /><img width="600" alt="Category-theoretic-approach-to-social-choice-theory-IMD" src="https://github.com/user-attachments/assets/58a23bf4-c036-4378-a0ac-278c26e6b7f5" /><br /><br />

---

### 🔄 The technical shifts I am accustomed to:

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
      <td>Formal Foundations <i>(e.g., Lambda Calculus, Category Theory: Typeclasses, ADTs, Functors & Monads, Algebraic Effects, Polymorphic Variants, Type|Kind-Level Programming, Phantom Types...)</i></td>
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
      <td>Code as (irrefutable) Mathematical Proof Trees <i>(i.e., Curry-Howard isomorphism)</i></td>
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
      <td>Domain-Driven & Context-Centric (see the work of <a href="https://urlr.me/2pkmja">Rico Fritzsche</a>)</td>
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
      <td>Type-Enforced Architecture++ <i>(e.g., TypeScript ➔ PureScript)</i></td>
    </tr>
    <tr>
      <td>Single-Runtime Language Lock-in</td>
      <td>Runtime-Agnostic Language <i>(Browser, Node/V8, Erlang/BEAM, ...)</i> (more explanations <a href="https://urlr.me/4cEkGH">here</a>)</td>
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

---

### 🧠 Philosophy: a healthy transfer of complexity

I want to reassure you on one point: I am aware of the complexity of my descriptions. All of this is not aimed at adding complexity for the sake of complexity, but rather at accommodating, at the same level, the increased complexity that comes with your growth. This should be seen as a **transfer** of complexity: as the company's internal logic becomes more complex (e.g., customer traffic, server fleet, internal teams...), the goal is to answer it with **dense conceptual buffers** that **capture** this complexity, thus avoiding the distortion of your interfaces, those of the developers, your internal organization, etc. I have the hardened, deep conviction that a rich technique relieves a whole group. Therefore, this aims less at intimidating than at offering you a credible vision of things, backed by **tangible elements**. In my opinion, good complexity is intentional, controlled complexity, as opposed to contingent and accidental complexity leaking down to the product itself, and felt by customers and/or developers.

<br />
<img width="600" alt="Screenshot 2026-07-18 at 18 59 25" src="https://github.com/user-attachments/assets/a52d34c9-23b7-4604-abac-62f2a3f065d6" />
<br />
<br />

A number of these choices are decisive in the context of an AI-oriented company policy. From an agentic point of view, an AI is notably provided with rails and guardrails (e.g., Hindley-Milner, System F...) that considerably reduce its stochastic search space.

---

### 💬 Let's chat!

If this short manifesto intrigues you, feel free to contact me for more in-depth discussions elsewhere, between **humans**!

On a technical level, I would be delighted to discuss: runtime agnosticism, Event Sourcing, PLT & compilers, FP, Category Theory, the internals of Postgres...

And/or on a more general level, let's talk about your **concrete projects**!

<img width="800" alt="WhatsApp Image 2026-07-18 at 19 19 43" src="https://github.com/user-attachments/assets/064ccc1b-4a94-4d2e-b520-091f7d70e7c4" />

_(Photo taken/stylized with a Kodak, in 2026, and in Scotland: I am a long-time runner, and I usually run the equivalent distance of 1 to 3 marathons a week, in settings as natural as possible)_
