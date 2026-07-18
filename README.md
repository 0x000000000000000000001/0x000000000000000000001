*🇬🇧 Looking for the English version? [Click here](./README.en.md)*

*✍️ 100% humain, rédigé par moi-même, sans IA. Je pense ce que j'écris.*

*💻 Je suis actuellement ouverts aux propositions d'entreprise (cofondation, CDI, freelance...)*

# 👋 Bonjour bonjour !

Je suis ingénieur/architecte logiciel/web, focalisé sur l'utilisation de la **programmation fonctionnelle pure** (FP), pour déjouer les **contraintes du monde réel**, et **exprimer un métier** avec un **haut degré de précision**. 

J'ai d'abord accumulé de l'expérience via le prisme de la programmation orientée-objet (OOP), avec des langages courants comme C/C++, PHP, TypeScript (et leurs frameworks)... mais j'ai toujours gardé une main sur la FP en parallèle. Avec les années, j'ai fini par rencontrer un certain nombre de [limites fondamentales](https://www.youtube.com/watch?v=wo84LFzx5nI) en OOP, indépendantes de ma volonté. Elles m'ont poussé à tourner la page, et à sacrifier une partie de mes connaissances, afin de me projeter vers l'un des [mouvements tectoniques](https://youtu.be/QyJZzq0v7Z4?t=2191) les plus profonds de l'industrie actuelle (OOP → hybrid FP style → FP), toujours en cours (e.g. [ici](https://github.com/IBM/fp-go) chez IBM, [là](https://github.com/gcanti/fp-ts) grâce à Unspash, les fortes [influences](https://doc.rust-lang.org/stable/book/ch13-00-functional-features.html?utm_source=chatgpt.com) sur Rust à Mozilla, ...). 

<br />
<img width="600" alt="images" src="https://github.com/user-attachments/assets/2246b10e-6d8d-449a-9307-d8b627263009" />
<br />
<br />

Pour autant, je suis très conscient des technologies encore à l'œuvre aujourd'hui dans l'industrie. Ma philosophie est donc **mésomorphique, hybride**, à l'image de nos écrans modernes (i.e. à cristaux liquides) : langage primaire et code **solides**, précis, structurés, concis et vérifiables (par la machine) ; mais runtime, code et langages secondaires **liquides**, flexibles et adaptables, prenant en compte l'historique et le legs d'une entreprise. Du côté de l'équipe technique : un environnement abordable, structuré, familier et fidèle à la pensée (autour du métier). Du côté de l'exécution du code (clients, contraintes générales...) : un environnement sur mesure, adapté à l'enjeu, aux contingences du moment et de l'endroit (e.g. résilience, vitesse, etc.). 

Scalabilité, Fiabilité, Maintenabilité. C'est sur cet alliage que mon attention s'est **polarisée** depuis plusieurs années, en concevant des systèmes qui maximisent **sans sacrifice** ces trois propriétés. Que ce soit rendre des écosystèmes modernes véritablement sécurisés et scalables, cibler des serveurs "legacy" sans sacrifier la sûreté moderne, ou pousser des bases de données relationnelles dans leurs limites physiques : mon office est de répondre très rapidement à des millions de requêtes par jour (pour les clients dans leur ensemble), sans bug (pour un client isolé), avec aisance et vélocité (pour l'équipe technique).

<br />
<img width="600" alt="strangler-fig-e1758297038747" src="https://github.com/user-attachments/assets/29ab8af8-a85a-480d-8b68-6e09aa5312b3" />
<br />
<br />

J'ajoute à cela un sujet important : le **pivot technologique (Transpilation & Strangler Fig Pattern)**. J'entends par là la capacité d'orchestrer la migration complète du code d'une entreprise (d'un écosystème/langage "legacy" vers un runtime natif ultra-performant comme Rust ou Go) sans **aucun** risque de réécriture _Big Bang_. À l'image du figuier étrangleur naturel, qui s'enroule progressivement autour d'un vieil arbre pour finir par le remplacer intégralement (sans jamais l'abattre brusquement), un langage FP bien conçu s'insère au sein de la base de code existante (via la FFI : Foreign Function Interface). Elle isole et sécurise ainsi mathématiquement la logique métier par **îlots**. Une fois le code métier assaini, le découplage est tel qu'il suffit de modifier la cible de transpilation pour **basculer** d'un environnement d'exécution à l'autre, en 10 secondes (ce moment est particulièrement gratifiant, en voici une preuve [à cet endroit](https://github.com/0x000000000000000000001/b8x.pub#-runtime-agnostic-in-the-real-world) : ici, un projet bascule d'un runtime/langage (JS) vers un autre (PHP), sans modifier la moindre ligne de code). On transfert la complexité du projet vers l'architecture de compilation, ce qui permet à l'entreprise de changer radicalement de classe de performance tout en continuant de livrer des fonctionnalités au quotidien. Les mêmes que d'habitude, mais : plus **vite**, beaucoup plus **fiable**, et beaucoup, beaucoup plus **loin**. Et bien sûr, ce qui a été fait une fois, pourra être refait 10 ans plus tard, avec un autre langage cible, mais bien plus rapidement : l'étape de l'insertion étant déjà faite, il n'y aura qu'à réécrire quelques FFIs, puis basculer. Tout simplement. Cela assure à l'entreprise une **mise à jour naturelle**, alignée **en permanence** sur les nouvelles technologies et les nouveaux standards de performance, sans sacrifier ce qu'elle sait faire de mieux : son métier, son produit propre.

Je pense fondamentalement, comme [Milewski](https://www.youtube.com/watch?v=XZl5DglVTCs), que l'avenir de la programmation réside dans la faculté d'**expression** d'idées mathématisées (invariants, effets, lois, etc.), avec des langages enracinés dans les théories modernes (e.g. Théorie des Catégories, HoTT, etc.). Comme j'ai pu l'écrire [sur mon blog](https://dev.to/0x1/zero-developers-in-2026-musk-is-right-but-wrong-1nm2), le code est de plus en plus assumé par l'IA, mais la programmation change de définition, se mathématise, et reste humaine : il ne s'agit plus de dire à la machine _comment_ faire, mais _quoi_ faire (sous forme d'arbre décisionnel), prisant ainsi tout paradigme de programmation allant en ce sens.

Voilà pour les grandes lignes, et la trajectoire d'ensemble !

Actuellement, je cherche un ambitieux projet à **fonder** ou à **booster**, dans lequel je crois à 100%.

### 🔬 Mes axes de recherche actuels

* 🧩 **Agnosticisme d'exécution (Runtime agnosticism)** : Je conçois une logique métier pure, découplée des environnements d'exécution spécifiques, traditionnellement associés aux langages mainstream de l'industrie. Mon travail actuel consiste à amener la programmation fonctionnelle stricte dans des [**endroits**](https://github.com/0x000000000000000000001/phpurs) où on la trouve rarement, en tirant parti d'écosystèmes massifs existants sans sacrifier la sûreté de typage avancée. J'ai la conviction profonde que l'ère des guerres de religion entre langages de programmation est **révolue**. Il est temps de profiter des forces de chaque langage (ex: Erlang pour la tolérance aux pannes, PHP pour le déploiement omniprésent, Node.js pour les I/O asynchrones, C/C++/Rust/Chez Scheme pour la vitesse d'exécution brute, etc.) en favorisant un dialogue intelligent entre eux. Cela peut notamment se faire via un langage suffisamment abstrait pour agir comme une couche universelle, sans souffrir du syndrome du *"plus petit dénominateur commun"* (ex: Haxe), et en offrant une FFI et une compilation optimisées/puissantes. Je parle plus longuement de ce sujet [dans cet article](https://dev.to/0x1/the-ultimate-polymorphism-purescript-as-a-universal-language-5gdi), et j'en ai fait une [preuve testable publiquement](https://github.com/0x000000000000000000001/b8x.pub#-runtime-agnostic-in-the-real-world), même si un petit nombre d'ingénieurs initiés au sujet le savent déjà (puisqu'ils ont aussi proposé eux-mêmes des compilateurs publics).

* ⚡ **Architectures "Lock-free"** : J'explore des patterns d'Event Sourcing intéressants ([POC](https://github.com/0x000000000000000000001/ccc-postgres-concurrency-proof/tree/feat/cco), que j'ai initialement discuté [ici](https://github.com/ricofritzsche/ccc-postgres-concurrency-proof/issues/1), également implémenté dans un [projet réel](https://github.com/0x000000000000000000001/b8x.pub#%EF%B8%8F-event-sourcing-architecture-postgresql-native)). Je me concentre sur la capacité à pousser des bases de données monolithiques (comme PostgreSQL) à une échelle FAANG (60k+ TPS) en utilisant des paradigmes sur-mesure comme le DDD sans agrégat (*Aggregateless DDD*), les *Context Collision Observers* (CCO) et l'optimistic batching. <br /><img width="600" alt="Screenshot 2026-07-18 at 18 42 49" src="https://github.com/user-attachments/assets/3218a122-d638-439e-9df1-50c978d46cb6" /><br />

* 📐 **FP pure et Théorie des Catégories** : J'utilise la rigueur mathématique non seulement pour la beauté de la théorie elle-même (merci [Milewski](https://bartoszmilewski.com) ❤️), mais pour résoudre des problèmes d'ingénierie notoirement difficiles : la concurrence, l'état distribué, l'invalidation de cache, les "machines à remonter le temps" (Time Travel Debugging), la symétrie architecturale, etc.

### 🔄 Les bascules techniques dont je suis coutumier :

<table>
  <thead>
    <tr>
      <th>Thème</th>
      <th>Avant</th>
      <th>Après</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5"><b>Paradigme</b></td>
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
      <td>Code as (irrefutable) Mathematical Proof Trees <i>(i.e. isomorphisme de Curry-Howard)</i></td>
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
      <td>Domain-Driven & Context-Centric (voir les travaux de <a href="https://urlr.me/2pkmja">Rico Fritzsche</a>)</td>
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
      <td>Runtime-Agnostic Language <i>(Browser, Node/V8, Erlang/BEAM, ...)</i> (plus d'explications <a href="https://urlr.me/4cEkGH">ici</a>)</td>
    </tr>
    <tr>
      <td rowspan="6"><b>Data & Performance</b></td>
      <td>CRUD</td>
      <td>High-Performance Event Sourcing & CQRS (exemple <a href="https://urlr.me/qSgyDM">ici</a>)</td>
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

### 🧠 Philosophie : un transfert de complexité sain

Je tiens à rassurer sur un point : j'ai conscience de la complexité de mes descriptions. Tout cela ne vise pas à complexifier pour complexifier, mais au contraire à accueillir, au même niveau, la complexité accrue qui accompagne votre croissance. Il faut voir cela comme un **transfert** de complexité : la logique interne de l'entreprise se compliquant (e.g. trafic des clients, parc de serveurs, équipes internes...), il s'agit d'y répondre par des **tampons conceptuels denses** qui **capturent** cette complexité, évitant ainsi de dénaturer vos interfaces, celles des développeurs, votre organisation interne, etc. J'ai la conviction indurée, profonde, qu'une technique riche soulage l'ensemble d'un groupe. Cela vise donc moins à intimider qu'à vous proposer une vision crédible des choses, **éléments tangibles** à l'appui. À mon sens, la bonne complexité est la complexité intentionnelle, contrôlée, en opposition à une complexité contingente et accidentelle, fuitant jusqu'au produit lui-même, et ressentie par les clients et/ou les développeurs.

*Note d'actualité : un certain nombre de ces choix s'unissent bien à une politique d'entreprise orientée IA. D'un point de vue agentique, une IA se voit notamment offrir des rails et des garde-fous (e.g. Hindley-Milner, System F...) qui réduisent considérablement son espace de recherche stochastique.*

### 💬 Discutons !

Si ce petit manifeste vous intrigue, n'hésitez pas à me contacter pour des échanges plus approfondis ailleurs, entre humains !

Sur un plan technique, je serais ravi d'échanger autour de : runtime agnosticism, Event Sourcing, PLT & compilers, FP, Category Theory, les entrailles de Postgres...

Et/ou sur un plan plus général, parlons de vos projets concrets !
