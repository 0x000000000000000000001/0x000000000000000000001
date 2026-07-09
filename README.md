*✍️ 100% humain, rédigé par moi-même, sans IA.*
*🇬🇧 Looking for the English version? [Click here](./README.en.md)*

# 👋 Bonjour bonjour !

Je suis ingénieur/architecte logiciel/web, focalisé sur l'utilisation de la **programmation fonctionnelle pure** pour débloquer des **contraintes extrêmes du monde réel**. Actuellement, je cherche un ambitieux projet à fonder ou à booster, dans lequel je crois à 100%.

Scalabilité, Fiabilité, Maintenabilité. C'est sur cet alliage que mon attention s'est **polarisée** depuis plusieurs années, en concevant des systèmes qui maximisent **sans sacrifice** ces trois propriétés. Que ce soit rendre des écosystèmes modernes véritablement sécurisés et scalables, cibler des serveurs "legacy" sans sacrifier la sûreté moderne, ou pousser des bases de données relationnelles dans leurs limites physiques : mon but est de répondre très rapidement à des millions de requêtes par jour (pour les clients dans leur ensemble), sans bug (pour un client isolé), avec aisance et vélocité (pour l'équipe technique).

### 🔬 Mes axes de recherche et priorités actuelles

* 🧩 **Agnosticisme d'exécution (Runtime agnosticism)** : Je conçois une logique métier pure, découplée des environnements d'exécution spécifiques. Mon travail actuel consiste à amener la programmation fonctionnelle stricte dans des [**endroits**](https://github.com/0x000000000000000000001/phpurs) où on la trouve rarement, en tirant parti d'écosystèmes massifs existants sans sacrifier la sûreté de typage avancée. J'ai la conviction profonde que l'ère des guerres de religion entre langages de programmation est **révolue**. Il est temps de profiter des forces de chaque langage (ex: Erlang pour la tolérance aux pannes, PHP pour le déploiement omniprésent, Node.js pour les I/O asynchrones, C/C++/Rust/Chez Scheme pour la vitesse d'exécution brute, etc.) en favorisant un dialogue intelligent entre eux. Cela se fait via un langage suffisamment abstrait pour agir comme une couche universelle, sans souffrir du syndrome du *"plus petit dénominateur commun"* (ex: Haxe), et en offrant une FFI et une compilation optimisées/puissantes.

* ⚡ **Architectures "Lock-free"** : J'explore des [**patterns d'Event Sourcing intéressants**](https://github.com/ricofritzsche/ccc-postgres-concurrency-proof/issues/1). Je me concentre sur la capacité à pousser des bases de données monolithiques (comme PostgreSQL) à une échelle digne des FAANG (60k+ TPS) en utilisant des paradigmes sur-mesure comme le DDD sans agrégat (*Aggregateless DDD*), les *Context Collision Observers* (CCO) et l'optimistic batching. 

* 📐 **FP Pure et Théorie des Catégories** : J'utilise la rigueur mathématique non seulement pour la beauté de la théorie elle-même (merci [Milewski](https://bartoszmilewski.com) ❤️), mais pour résoudre des problèmes d'ingénierie notoirement difficiles : la concurrence, l'état distribué, l'invalidation de cache, les "machines à remonter le temps" (Time Travel Debugging), la symétrie architecturale, etc.

### 🔄 Les bascules techniques dont je suis coutumier :

**(Paradigme)**
* Ad-hoc Constructs ➔ Formal Foundations *(e.g. Lambda Calculus, Category Theory: Typeclasses, ADTs, Functors & Monads, Algebraic Effects, Polymorphic Variants, Type|Kind-Level Programming, Phantom Types...)*
* GoF Design Patterns ➔ Algebraic Abstractions*
* Imperative ➔ Declarative
* Statements ➔ Expressions
* Code as Text ➔ Code as (irrefutable) Mathematical Proof Trees *(i.e. isomorphisme de Curry-Howard)* 

**(Safety)**
* Implicit Hell ➔ Explicit Types, Constraints & Effects
* Primitive Obsession ➔ Zero-Cost Abstractions
* Defensive Programming ➔ MISU *(Make Illegal States Unrepresentable)*
* Runtime Errors ➔ Compile-Time Safety *(Hindley-Milner, System F...)*
* Bug Detection ➔ Bug Prevention

**(Architecture)**
* Database-Driven & Framework-Driven ➔ Domain-Driven & Context-Centric (voir les travaux de [Rico Fritzsche](https://urlr.me/2pkmja))
* Horizontal Layers ➔ Hexagonal & Vertical Layers
* Leaky Abstractions ➔ Hermetic Abstractions
* Human Discipline ➔ Type-Enforced Architecture++ *(e.g. TypeScript ➔ PureScript)*
* Single-Runtime Language Lock-in ➔ Runtime-Agnostic Language *(Browser, Node/V8, Erlang/BEAM, ...)* (plus d'explications [ici](https://urlr.me/4cEkGH))

**(Data & Performance)**
* CRUD ➔ High-Performance Event Sourcing & CQRS (exemple [ici](https://urlr.me/qSgyDM))
* Nested Mutations ➔ Immutables & Optics *(Lenses, Prisms...)*
* UI: 2-Way Data Binding ➔ TEA *(The Elm Architecture)*
* Single-Threaded ➔ Concurrent & Parallel-Threaded
* RAM-heavy (€€€) ➔ Disk-optimized (€)
* API & Ops Time in N ms ➔ ... in N/10 or N/100 ms

### 🧠 Philosophie : un transfert de complexité sain

Je tiens à rassurer sur un point : j'ai conscience de la complexité de mes descriptions. Tout cela ne vise pas à complexifier pour complexifier, mais au contraire à accueillir, au même niveau, la complexité accrue qui accompagne votre croissance. Il faut voir cela comme un transfert de complexité : la logique interne de l'entreprise se compliquant (e.g. trafic des clients, parc de serveurs, équipes internes...), il s'agit d'y répondre par des **tampons conceptuels denses** qui capturent cette complexité, évitant ainsi de dénaturer vos interfaces, celles des développeurs, votre organisation interne, etc. J'ai la conviction indurée, profonde, qu'une technique riche soulage l'ensemble d'un groupe. Cela vise donc moins à intimider qu'à vous proposer une vision crédible des choses, **éléments tangibles** à l'appui. À mon sens, la bonne complexité est la complexité intentionnelle, contrôlée, en opposition à une complexité contingente et accidentelle, fuitant jusqu'au produit lui-même, et ressentie par les clients.

*Note d'actualité : un certain nombre de ces choix s'unissent bien à une politique d'entreprise orientée IA. D'un point de vue agentique, une IA se voit notamment offrir des rails et des garde-fous (e.g. Hindley-Milner, System F...) qui réduisent considérablement son espace de recherche stochastique.*

### 💬 Discutons !

Si ce petit manifeste vous intrigue, n'hésitez pas à me contacter pour des échanges plus approfondis ailleurs, entre humains !

Sur un plan technique, je serais ravi d'échanger autour de : Runtime agnosticism, Event Sourcing, PLT & Compilers, FP, Category Theory, les entrailles de Postgres...

Et/ou sur un plan général, parlons de vos projets concrets !
