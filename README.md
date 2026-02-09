# my-awesome [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome links, frameworks, libraries and software.

## Index of system design topics
- [Performance vs scalability](#performance-vs-scalability)
- [Latency vs throughput](#latency-vs-throughput)
- [Availability vs consistency](#availability-vs-consistency)
    - [CAP theorem](#cap-theorem)
- [Consistency patterns](#consistency-patterns)
- [Availability patterns](#availability-patterns)
- [Domain name system](#domain-name-system)
- [Content delivery network](#content-delivery-network)
- [Load balancer](#load-balancer)
- [Reverse proxy (web server)](#reverse-proxy-web-server)
- [Application layer](#application-layer)
    - [Microservices](#microservices)
- [Database](#database)
    - [Relational database management system (RDBMS)](#relational-database-management-system-rdbms)
    - [NoSQL](#nosql)
- [Cache](#cache)
- [Asynchronism](#asynchronism)
    - [Message queues](#message-queues)
- [Communication](#communication)
- [Security](#security)

## Additional Topics
- [Low Level Design](#low-level-design)
- [Software Architecture](#software-architecture)
- [API](#api)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
- [Design Patterns](#design-patterns)
- [Object Oriented Design](#object-oriented-design)
- [Git](#git)
- [Distributed Systems](#distributed-systems)
- [ElasticSearch](#elasticsearch)
- [Problem-Solving](#problem-solving)
- [Common](#common)
- [Spring](#spring)
- [Java](#java)
- [Kubernetes](#kubernetes)
- [Platform Engineering](#platform-engineering)
- [Behavioural](#behavioural)
- [Awesome](#awesome)
- [Remote First](#remote-first)
- [To watch](#to-watch)
- [Resume](#resume)
- [Go](#go)

### Performance vs scalability
- [How we scaled the GitHub API with a sharded, replicated rate limiter in Redis](https://github.blog/2021-04-05-how-we-scaled-github-api-sharded-replicated-rate-limiter-redis/)
- [High-Performance Programming](https://www.youtube.com/@HighPerformanceProgramming/playlists)

### Latency vs throughput
- [Latency numbers every programmer should know](https://github.com/sirupsen/napkin-math)

### Availability vs consistency
- [Revolutionizing Money Movements at Scale with Strong Data Consistency](https://www.uber.com/en-EG/blog/money-scale-strong-data/)

#### CAP theorem
- [System design fundamentals: What is the CAP theorem?](https://www.educative.io/blog/what-is-cap-theorem)

### Consistency patterns
- [Eventual vs Strong Consistency in Distributed Databases](https://hackernoon.com/eventual-vs-strong-consistency-in-distributed-databases-282fdad37cf7)

### Availability patterns
- [Building Resilient Microservices: Strategies for Handling Failures](https://dip-mazumder.medium.com/building-resilient-microservices-strategies-for-handling-failures-in-stock-price-notification-629a3e206f41)
- [Retries strategies in distributed systems](https://www.geeksforgeeks.org/system-design/retries-strategies-in-distributed-systems/)
- [10 Tips for Building Resilient Payment Systems](https://shopify.engineering/building-resilient-payment-systems)

### Domain name system
- [A Crash Course in DNS](https://blog.bytebytego.com/p/a-crash-course-in-dns-domain-name)

### Content delivery network
- [What is a CDN?](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)

### Load balancer
- [Introduction to modern network load balancing and proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
- [Load Balancer vs. Reverse Proxy vs. API Gateway](https://medium.com/geekculture/load-balancer-vs-reverse-proxy-vs-api-gateway-e9ec5809180c)

### Reverse proxy (web server)
- [What is a Reverse Proxy?](https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/)

### Application layer
- [High-Level System Architecture of Booking.com](https://medium.com/@sahintalha1/high-level-system-architecture-of-booking-com-06c199003d94)

#### Microservices
- [Principles for Microservice Design: Think IDEALS, Rather than SOLID](https://www.infoq.com/articles/microservices-design-ideals/)
- [What is a Modular Monolith?](https://www.milanjovanovic.tech/blog/what-is-a-modular-monolith)
- [Principles Of Microservices by Sam Newman](https://www.youtube.com/watch?v=PFQnNFe27kU)
- [Best Practices for Building a Microservice Architecture](https://www.vinaysahni.com/best-practices-for-building-a-microservice-architecture)
- [Microservice Architecture and its 10 Most Important Design Patterns](https://towardsdatascience.com/microservice-architecture-and-its-10-most-important-design-patterns-824952d7fa41)
- [Transactions in a Microservice World](https://wso2.com/whitepapers/transactions-in-a-microservice-world/)
- [Resiliency in Microservices: A Guide to Circuit Breaker Pattern](https://dip-mazumder.medium.com/best-practices-for-error-handling-a-guide-to-circuit-breaker-patterns-41d45ffc02ac)

### Database
- [15-445/645 Intro to Database Systems (Fall 2019)](https://www.youtube.com/playlist?list=PLSE8ODhjZXjbohkNBWQs_otTrBTrjyohi)
- [Things I Wished More Developers Knew About Databases](https://rakyll.medium.com/things-i-wished-more-developers-knew-about-databases-2d0178464f78)
- [How to Scale SQL and NoSQL Databases](https://betterprogramming.pub/scaling-sql-nosql-databases-1121b24506df)
- [What are ACID properties in a database?](https://www.educative.io/answers/what-are-acid-properties-in-a-database)
- [Database Durability in a nutshell](https://towardsdev.com/database-durability-in-a-nutshell-34c9f61dcbc3)
- [Database Optimization: Troubleshoot Slow Database Query](https://dip-mazumder.medium.com/database-optimization-troubleshoot-slow-database-query-b66f3dbea42f)
- [Cracking the SQL Interview](https://github.com/xoraus/CrackingTheSQLInterview)
- [SQL Mastery for Interviews](https://github.com/Imran53/SQL-Mastery-for-Interviews)

#### Relational database management system (RDBMS)
- [A Deep Dive into Database Concurrency Control](https://www.alibabacloud.com/blog/a-deep-dive-into-database-concurrency-control_596779)
- [How does database sharding work?](https://planetscale.com/blog/how-does-database-sharding-work?utm_id=newsletter)
- [The growing pains of database architecture](https://www.figma.com/blog/how-figma-scaled-to-multiple-databases/)
- [8 Week SQL Challenge](https://8weeksqlchallenge.com/)
- [Database Indexing under the hood](https://towardsdev.com/database-indexing-under-the-hood-5841ac77f7de)
- [Mastering the Art of SQL Interviews: Unlocking the Solutions to Common and Complex Queries](https://medium.com/javarevisited/mastering-the-art-of-sql-interviews-unlocking-the-solutions-to-common-and-complex-queries-302c2aba9620)
- [database replication](https://www.techtarget.com/searchdatamanagement/definition/database-replication)
- [Understanding Database Isolation Levels](https://medium.com/nerd-for-tech/understanding-database-isolation-levels-c4ebcd55c6b9)

#### NoSQL
- [MongoDB Replication](https://www.mongodb.com/basics/replication)
- [MongoDB vs PostgreSQL: What to consider when choosing a database](https://www.educative.io/blog/mongodb-versus-postgresql-databases)

### Cache
- [Caching Strategies and How to Choose the Right One](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)
- [A Comprehensive Guide to Distributed Caching](https://blog.devgenius.io/a-comprehensive-guide-to-distributed-caching-827f1fa5a184)
- [How DoorDash Standardized and Improved Microservices Caching](https://doordash.engineering/2023/10/19/how-doordash-standardized-and-improved-microservices-caching/amp/)
- [Mastering the Art of Caching for System Design Interviews](https://www.designgurus.io/blog/caching-system-design-interview)

### Asynchronism
- [Asynchronous computing @Facebook: Driving efficiency and developer productivity at Facebook scale](https://engineering.fb.com/2020/08/17/production-engineering/async/)
- [The Complete Guide to Event-Driven Architecture](https://solace.com/what-is-event-driven-architecture/)
- [Error Handling in Event-Driven Systems](https://levelup.gitconnected.com/error-handling-in-event-driven-systems-1f0a7ef2cfb7)
- [Managing Back Pressure in reactive Streams](https://medium.com/@vikas.taank_40391/managing-back-pressure-in-reactive-streams-c64f91a10adf)

#### Message queues
- [Introduction to Message Brokers: Part 1: Apache Kafka vs RabbitMQ](https://hackernoon.com/introduction-to-message-brokers-part-1-apache-kafka-vs-rabbitmq-8fd67bf68566)
- [Message Queues & You – 12 Reasons to Use Message Queuing](https://stackify.com/message-queues-12-reasons/)
- [Understanding the Differences Between RabbitMQ and Kafka](https://tanzu.vmware.com/content/blog/understanding-the-differences-between-rabbitmq-vs-kafka)
- [Dynein: Building an Open-source Distributed Delayed Job Queueing System](https://medium.com/airbnb-engineering/dynein-building-a-distributed-delayed-job-queueing-system-93ab10f05f99)
- [Rapid Event Notification System at Netflix](https://netflixtechblog.com/rapid-event-notification-system-at-netflix-6deb1d2b57d1)
- [Behind the scenes: McDonald’s event-driven architecture](https://medium.com/mcdonalds-technical-blog/behind-the-scenes-mcdonalds-event-driven-architecture-51a6542c0d86)

### Communication
- [Network protocols and proxies: system design interview concepts (1 of 9)](https://igotanoffer.com/blogs/tech/network-protocols-proxies-system-design-interview?pos=13&_sid=ec68c0f85&_ss=r)
- [A Tour of Netty](https://medium.com/geekculture/a-tour-of-netty-5020ecee5494)

### Security
- [OWASP Top 10](https://www.synopsys.com/glossary/what-is-owasp-top-10.html)
- [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist?fbclid=IwAR3jfNqAlHZwOL74y9Z0ejk7YPnQmKifW3oVBhVcZ4h6jphH242m0LVD4pQ)
- [10 Database Security Best Practices You Should Know](https://www.tripwire.com/state-of-security/database-security-best-practices-you-should-know)
- [CS 253 Web Security](https://www.youtube.com/playlist?list=PL1y1iaEtjSYiiSGVlL1cHsXN_kvJOOhu-)
- [JSON Web Tokens and Authentication](https://newsletter.systemdesigncodex.com/p/json-web-tokens-and-authentication)
- [What is OIDC and where and why it is used](https://medium.com/@martin.hodges/an-is-oidc-and-where-and-why-it-is-used-e03bcbcf1703)

---

### Low Level Design
- [awesome-low-level-design](https://github.com/ashishps1/awesome-low-level-design)

### Software Architecture
- [System Design Course](https://github.com/karanpratapsingh/system-design)
- [System Design and Architecture](https://github.com/puncsky/system-design-and-architecture)
- [Software Architecture GOTO Conferences](https://www.youtube.com/playlist?list=PLEx5khR4g7PJELLTYwXZHcimWAwTUaWGA)
- [Introduction to architecting systems for scale](https://lethain.com/introduction-to-architecting-systems-for-scale/)
- [Web Architecture 101](https://medium.com/storyblocks-engineering/web-architecture-101-a3224e126947)
- [CQRS: What? Why? How?](https://sderosiaux.medium.com/cqrs-what-why-how-945543482313)
- [Software Architecture Concepts](https://blog.cmpsamurai.com/series/software-architecture)
- [Domain Driven Design and Development In Practice](https://www.infoq.com/articles/ddd-in-practice/)
- [Hexagonal Architectures — the sequel](https://medium.com/mcdonalds-technical-blog/hexagonal-architectures-the-sequel-073c9ee79385)
- [Practical DDD — Setting The Right Foundations](https://medium.com/augury-research-and-development/practical-ddd-part-1-setting-the-right-foundations-5b7e4b16c9e8)
- [What I learned from the book Software Architecture: The Hard Parts](https://medium.com/@techworldwithmilan/what-i-learned-from-the-software-architecture-the-hard-parts-0498c9eae88e)
- [Driving architectural decisions with a simple decentralized framework](https://medium.com/@techworldwithmilan/driving-architectural-decisions-with-a-simple-decentralized-framework-32367f19e383)

### API
- [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
- [How to design an efficient Idempotency API](https://levelup.gitconnected.com/how-to-design-an-efficient-idempotency-api-e664fa2954bb)
- [API Best Practices: Webhooks, Deprecation, and Design](https://zapier.com/engineering/api-best-practices/)
- [How We Design Our APIs at Slack](https://slack.engineering/how-we-design-our-apis-at-slack/)
- [REST API Design Best Practices](https://medium.com/@techworldwithmilan/rest-api-design-best-practices-2eb5e749d428)
- [Efficient Concurrency Management: Optimistic Locking and Message Queues for Room Reservation API](https://blog.devops.dev/optimistic-locking-and-message-queues-solving-concurrency-challenges-in-room-reservation-ca0e661b63fd)

### Data Structures and Algorithms
- [Abdul Bari](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O)
- [Data Structures & Algorithms I Used Working at Tech Companies](https://blog.pragmaticengineer.com/data-structures-and-algorithms-i-actually-used-day-to-day/)

### Design Patterns
- [guru-design-patterns](https://refactoring.guru/design-patterns)
- [SourceMaking-design-patterns](https://sourcemaking.com/)
- [How to select a Design Pattern?](https://medium.com/@techworldwithmilan/how-to-select-a-design-pattern-567181b90e8c)

### Object Oriented Design
- [A Solid Guide to SOLID Principles](https://www.baeldung.com/solid-principles)
- [Object-Oriented Programming (OOP) in JAVA](https://vaheaslanyan7.medium.com/object-oriented-programming-oop-in-java-00ff487c98c9)
- [Preparing for a Java Interview? Here are the Top 19 OOPS Questions That You Need to Know](https://medium.com/javarevisited/preparing-for-a-java-interview-here-are-the-top-19-oops-questions-that-you-need-to-know-6cc6dde3d4c3)
- [Top 14 Interview questions On Abstraction principle to ace your next Object-Oriented Programming Interview](https://medium.com/javarevisited/master-the-art-of-object-oriented-programming-expert-recommended-abstraction-questions-for-java-d82f8dfc3ff4)

### Git
- [How to Git as a Team](https://www.robinwieruch.de/git-team-workflow/)
- [Git workflow strategies: Multiple teams in a single repository](https://blog.logrocket.com/git-workflow-strategies-multiple-teams-single-repository/)
- [Best Practices for Branch Naming in Git for Successful CI/CD Implementation](https://awsomeclouds.com/best-practices-for-branch-naming-in-git-for-successful-ci-cd-implementation-f79b7ee2f09c)
- [How to Split Pull Requests – Good Practices, Methods and Git Strategies](https://www.thedroidsonroids.com/blog/splitting-pull-request)

### Distributed Systems
- [MIT 6.824 Distributed Systems (Spring 2020)](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)
- [Avoiding Double Payments in a Distributed Payments System](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb)
- [A Guide to Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing)
- [How to do distributed locking](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html)
- [Scaling services with Shard Manager](https://engineering.fb.com/2020/08/24/production-engineering/scaling-services-with-shard-manager/)
- [Handling time zones in distributed systems](https://blogs.oracle.com/javamagazine/post/java-timezone-part-1)

### ElasticSearch
- [Elasticsearch: What It Is, How It Works, And What It’s Used For](https://www.knowi.com/blog/what-is-elastic-search/)
- [Elasticsearch Architecture IX: Document Versioning & Optimistic Concurrency Control](https://braineanear.medium.com/elasticsearch-architecture-ix-document-versioning-optimistic-concurrency-control-52078843eef5)
- [The Complete Guide to the ELK Stack](https://logz.io/learn/complete-guide-elk-stack/#latest-on-the-elk-stack)
- [Create an advanced search engine with PostgreSQL](https://xata.io/blog/postgres-full-text-search-engine?ref=architecturenotes.co)

### Problem-Solving
- [Coding Interview Questions](https://github.com/ombharatiya/FAANG-Coding-Interview-Questions)
- [The Complete FAANG Preparation](https://github.com/AkashSingh3031/The-Complete-FAANG-Preparation)
- [How to Rock the Coding Interview – Tips That Helped Me Land Job Offers](https://www.freecodecamp.org/news/coding-interviews-for-dummies-5e048933b82b/)
- [14 Patterns to Ace Any Coding Interview Question](https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed)

### Common
- [You’re Not a Senior Software Engineer](https://medium.com/vanguards-of-code/youre-not-a-senior-software-engineer-9056ef9ffb96)
- [Rules of Thumb for Software Development Estimations](https://vadimkravcenko.com/shorts/project-estimates/?utm_source=programmingdigest&utm_medium&utm_campaign=1629&fbclid=IwAR1Imzensg3WfXo2eQPFqJwaIPxMCZHBr6ueDDHr_jMILHVs6HvEe-UI25w&mibextid=S66gvF)
- [On Being A Senior Engineer](https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)
- [How to Become a Good Backend Engineer (Fundamentals)](https://medium.com/@hnasr/how-to-become-a-good-backend-engineer-fundamentals-4dcc4a16ce55)
- [The Product-Minded Software Engineer](https://blog.pragmaticengineer.com/the-product-minded-engineer/)
- [A practical guide to writing technical specs](https://stackoverflow.blog/2020/04/06/a-practical-guide-to-writing-technical-specs/)
- [Post mortem on Linear incident from Jan 24th, 2024](https://linear.app/blog/linear-incident-on-jan-24th-2024)
- [How To Deal With Technical Debt](https://medium.com/@techworldwithmilan/how-to-deal-with-technical-debt-b0065c1a794d)
- [Writing an engineering strategy](https://lethain.com/eng-strategies/)
- [5 ways to review code without wasting everyone’s time](https://medium.com/volvo-cars-engineering/5-ways-to-review-code-without-wasting-everyones-time-aedeecc51094)

### Spring
- [Top Spring Framework Interview Questions](https://www.baeldung.com/spring-interview-questions)
- [How to handle incoming requests in Java with Spring Boot](https://medium.com/@burakkocakeu/how-to-handle-incoming-requests-in-java-with-spring-boot-b46cb35ed520)
- [Mastering Testcontainers for Better Integration Tests](https://www.youtube.com/watch?v=zfN8m9Dh9cs)
- [15+ things you need to know when you want to use Spring @Transactional really well](https://levelup.gitconnected.com/15-things-you-need-to-know-when-you-want-to-use-spring-transactional-really-well-fc6f5ec207ac)
- [How To Authenticate Your Spring Boot Application With Keycloak](https://betterprogramming.pub/how-to-authenticate-your-spring-boot-application-with-keycloak-1e9ccb5f2478)
- [Spring Security Fundamentals 2022](https://www.youtube.com/playlist?list=PLEocw3gLFc8X_a8hGWGaBnSkPFJmbb8QP)
- [Micrometer and Zipkin: How to Trace HTTP Requests in Spring Boot 3](https://www.appsdeveloperblog.com/micrometer-and-zipkin-in-spring-boot/)
- [Mastering Backend Development with Java Spring Boot: Best Practices and Pro Tips](https://itznihal.medium.com/mastering-backend-development-with-java-spring-boot:best-practices-and-pro-tips-3fc0f501418e)
- [A Guide to Understanding and Debugging SQL Execution Plans in Spring Boot](https://dev.to/jackynote/a-guide-to-understanding-and-debugging-sql-execution-plans-in-spring-boot-5ade)
- [Spring Data JPA, Spring Data R2DBC & Hibernate Reactive](https://medium.com/geekculture/spring-data-jpa-spring-data-r2dbc-hibernate-reactive-bcc43e321566)
- [Optimistic locking with JPA and Hibernate](https://vladmihalcea.com/optimistic-locking-version-property-jpa-hibernate/)
- [Hexagonal architecture and Domain Driven Design](https://dev.to/onepoint/hexagonal-architecture-and-domain-driven-design-fio)

### Java
- [Java Practices](http://www.javapractices.com/home/HomeAction.do)
- [A Complete Guide on ExecutorService In Java](https://medium.com/javarevisited/a-complete-guide-on-executorservice-in-java-67528f1a535b)
- [Generics in Java](https://salithachathuranga94.medium.com/generics-in-java-3c791555e924)
- [CompletableFuture- Advance Deep Dive](https://medium.com/@vikas.taank_40391/completablefuture-advance-deep-dive-369664e8d218)
- [The Power of Java Stream API](https://medium.com/@AlexanderObregon/the-power-of-java-stream-api-d7c0ab7e4c5a)
- [JVM internals for the Java job interview](https://medium.com/@dalibor.plavcic/jvm-internals-for-the-java-job-interview-83257d038134)
- [Java21 Features you must know](https://medium.com/@vikas.taank_40391/java21-features-you-must-know-40f57035e858)
- [A Comprehensive Journey from Java 8 to Java 21 with Code Examples of Essential API Enhancements](https://rathod-ajay.medium.com/a-comprehensive-journey-from-java-8-to-java-21-with-code-examples-of-essential-api-enhancements-6817d2ab3ba8)
- [Java Concurrency 101: Understanding Multithreading Fundamentals](https://dip-mazumder.medium.com/java-concurrency-101-understanding-multithreading-fundamentals-e5ed48b04ca5)
- [Understanding Java’s Garbage Collection](https://medium.com/@AlexanderObregon/understanding-javas-garbage-collection-bc141a2ef31f)
- [The Race Condition I Encountered in My Work](https://medium.com/geekculture/the-race-condition-i-encountered-in-my-work-6fc47ac637e1)

### Kubernetes
- [A guide to Kubernetes architecture](https://opensource.com/article/22/2/kubernetes-architecture)
- [The Layman’s Guide to Kubernetes: Understanding Containerization and More](https://medium.com/javarevisited/the-laymans-guide-to-kubernetes-understanding-containerization-and-more-f48ef16d3f8f)
- [Kubernetes production best-practices](https://github.com/learnk8s/kubernetes-production-best-practices)
- [List of terminal commands for Kubernetes](https://awstip.com/list-of-terminal-commands-for-kubernetes-ffc63f0dcec0)
- [Understanding Kubernetes Architecture: A Comprehensive Guide](https://devopscube.com/kubernetes-architecture-explained/)
- [Implementing distributed tracing with Jaeger & Opentelemetry on Kubernetes](https://medium.com/@akashjoffical08/implement-distributed-tracing-with-jaeger-opentelemetry-on-kubernetes-3e35cb77b536)
- [Making Sense of Kubernetes CPU Requests And Limits](https://medium.com/@jettycloud/making-sense-of-kubernetes-cpu-requests-and-limits-390bbb5b7c92)
- [A Hands-on Kubernetes Network Troubleshooting Journey](https://itnext.io/a-hands-on-kubernetes-network-troubleshooting-journey-c2b051ce6761)
- [How to Achieve Zero-Downtime Application with Kubernetes](https://www.qovery.com/blog/how-to-achieve-zero-downtime-application-with-kubernetes/)
- [OWASP Kubernetes Top 10: A Comprehensive Guide](https://medium.com/@seifeddinerajhi/owasp-kubernetes-top-10-a-comprehensive-guide-f03af6fd66ed)

### Platform Engineering
- [Build a Lightweight Internal Developer Platform with Argo CD and Kubernetes Labels](https://itnext.io/build-a-lightweight-internal-developer-platform-with-argo-cd-and-kubernetes-labels-4c0e52c6c0f4)

### Behavioural
- [7 BEST Behavioural Interview Questions & Answers!](https://www.youtube.com/watch?v=ZLtO_7LjzVg&t=685s)
- [ALUES-BASED Interview Questions And Answers! (How To Pass A Values Based Interview!)](https://www.youtube.com/watch?v=e5UE9dFYSd8)
- [Would you hire your boss? The top ten behavioral interview questions you should be asking your future boss.](https://www.linkedin.com/pulse/would-you-hire-your-boss-top-ten-behavioral-interview-paul-wyman/ )
- [8 Smart Questions To Ask Hiring Managers In A Job Interview](https://www.youtube.com/watch?v=Y95eI-ek_E8)
- [How To Prepare for a Behavioral Job Interview](https://www.thebalancemoney.com/behavioral-job-interviews-2058575)
- [Job Interview Questions, Answers, and Tips To Prepare](https://www.thebalancemoney.com/job-interview-questions-and-answers-2061204)
- [10 Behavioral Interview Questions for Software Engineers](https://www.indeed.com/career-advice/interviewing/software-engineer-behavioral-interview-questions)
- [7 Time Management Interview Questions](https://www.indeed.com/career-advice/interviewing/time-management-interview-questions)
- [New Job? Negotiate as if your life depends on it](https://www.medhat.dev/blog/negotiate-salary)
- [The Secret Art of Salary Negotiation](https://www.nicksingh.com/posts/the-secret-art-of-salary-negotiation#section1)
- [Salary Negotiation: Make More Money, Be More Valued](https://www.kalzumeus.com/2012/01/23/salary-negotiation/)
- [How to Speak](https://www.youtube.com/watch?v=Unzc731iCUY)
- [Awesome Behavioral Interviews](https://github.com/ashishps1/awesome-behavioral-interviews)
- [How To Respond To Feedback You Disagree With](https://developingskills.substack.com/p/how-to-respond-to-feedback-you-disagree)
- [How do you give direct feedback but still care about your people?](https://medium.com/@techworldwithmilan/how-do-you-give-direct-feedback-but-still-care-about-your-people-f119e8a8f761)

### Awesome
- [The System Design Primer](https://github.com/donnemartin/system-design-primer)
- [ByteByteGo](https://www.youtube.com/@ByteByteGo)
- [crack-the-system-design-interview](https://tianpan.co/notes/2016-02-13-crack-the-system-design-interview)
- [System Design Interview Questions – Concepts You Should Know](https://www.freecodecamp.org/news/systems-design-for-interviews/)
- [How to answer system design interview questions](https://igotanoffer.com/blogs/tech/system-design-interview-questions?pos=1&_sid=ec68c0f85&_ss=r)
- [System Design Interview Survival Guide (2023): Preparation Strategies and Practical Tips](https://levelup.gitconnected.com/system-design-interview-survival-guide-2023-preparation-strategies-and-practical-tips-ba9314e6b9e3)
- [18 System Design Concepts Every Engineer Must Know Before the Interview](https://www.designgurus.io/blog/system-design-interview-fundamentals)
- [System Design Concepts You NEED to Know](https://www.youtube.com/playlist?list=PL9nWRykSBSFjU7UGR37SFfOb1oMYLNhag)
- [Awesome System Design Resources](https://github.com/ashishps1/awesome-system-design-resources/blob/main/README.md#system-design-interview-problems)
- [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability)
- [awesome-java](https://github.com/akullpp/awesome-java)
- [interviews](https://github.com/kdn251/interviews)
- [coding-interview-university](https://github.com/jwasham/coding-interview-university)
- [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd)
- [15 Best Data Structure, Algorithms, and Programming Courses to Crack Coding Interviews](https://medium.com/javarevisited/10-data-structure-algorithms-and-programming-courses-to-crack-any-coding-interview-e1c50b30b927)
- [Circleci Engineering](https://circleci.com/blog/tag/engineering/)
- [10 GitHub Repos every developer will need!](https://dev.to/ahmedadel/10-github-repos-every-developer-will-need-cji)
- [Clean Code Notes](https://github.com/JuanCrg90/Clean-Code-Notes?fbclid=IwAR39TJejBvxXglZU9Y_UYcLqyknA4zHtnoNoYVivJpyIxWPaBUl_Mwixnhg)
- [Operating Systems Notes](https://applied-programming.github.io/Operating-Systems-Notes/)
- [Gitlab Engineering](https://about.gitlab.com/handbook/engineering/)
- [Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook)
- [Awesome Terraform](https://github.com/shuaibiyy/awesome-terraform)
- [Awesome Argo](https://github.com/akuity/awesome-argo)
- [Preparing for the Systems Design and Coding Interview](https://blog.pragmaticengineer.com/preparing-for-the-systems-design-and-coding-interviews/)
- [Beyond the basics](https://www.youtube.com/playlist?list=PL9ExMy1CBZjnsv2WXFKxXNf41iT1pdT2Q)
- [Path to Senior Engineer handbook](https://github.com/jordan-cutler/path-to-senior-engineer-handbook)
- [Tech Company Engineering Blogs](https://github.com/JohnCrickett/SystemDesign/tree/main/engineering-blogs)
- [system-design-101](https://github.com/ByteByteGoHq/system-design-101)

### Remote First
- [Careem](https://www.careem.com/)
- [Camunda](https://camunda.com/)
- [Turing](https://www.turing.com/)
- [Mentormate](https://mentormate.com/)
- [Procore technologies](https://www.procore.com/en-ae)
- [Wizeline](https://www.wizeline.com/)
- [100+ Fully Remote Companies with Top Work From Home Jobs](https://remotive.com/blog/remote-companies/)
- [Hiring Without Whiteboards](https://github.com/poteto/hiring-without-whiteboards)
- [Get.it](https://www.get.it/)
- [Sunsoftonline](https://www.sunsoftonline.com/)

### To watch
- [Working Effectively with Legacy Code • Michael Feathers & Christian Clausen](https://www.youtube.com/watch?app=desktop&list=PLEx5khR4g7PJbSLmADahf0LOpTLifiCra&v=P_6eDL1aqtA&feature=youtu.be)
- [The Phoenix Project: A Must-Read for Anyone in IT](https://www.youtube.com/watch?app=desktop&v=6QNdL1I7OTM)
- [The Unicorn Project: A Must-Read for Every DevOps Enthusiast](https://www.youtube.com/watch?app=desktop&v=I0vf9CtWGDc)
- [Coaching Senior Developers by Will Ray -- ng-sydney October 2018](https://www.youtube.com/watch?v=xifesQQF5aU)
- [How principled coders outperform the competition](https://www.youtube.com/watch?app=desktop&v=q1qKv5TBaOA&ab_channel=Coderized)
- [How to Do Code Reviews Like a Human](https://www.youtube.com/watch?v=0t4_MfHgb_A)
- [The Only Unbreakable Law](https://www.youtube.com/watch?v=5IUj1EZwpJY)
- [Software Engineering Interview Prep](https://www.youtube.com/playlist?list=PLrtCHHeadkHptUb0gduz9pxLgvtKWznKj)
- [System Design Interview Prep](https://www.youtube.com/playlist?list=PLrtCHHeadkHp92TyPt1Fj452_VGLipJnL)
- [Writing cleaner code with Domain Driven Design by Paul van der Slot](https://www.youtube.com/watch?v=3t0tZTOGk08)

### Resume
- [Want to work @FAANG companies? Start with a Great Resume](https://typefully.com/ywkem/vm1T86a)
- [10 common mistakes in writing resume](https://www.aabouzaid.com/2023/05/10-common-resume-cv-mistakes.html?m=1)

### Go
- [podinfo](https://github.com/stefanprodan/podinfo)
- [Introducing basic CQRS by refactoring a Go project](https://threedots.tech/post/basic-cqrs-in-go/)
- [Finding The Best Go Project Structure — Part 1](https://itnext.io/finding-the-best-go-project-structure-part-1-5290bc1d869d)
- [Getting Started with OpenTelemetry in distributed Go Microservices](https://medium.com/wesovilabs/getting-started-with-opentelemetry-in-distributed-go-microservices-192e7e21bd7c)