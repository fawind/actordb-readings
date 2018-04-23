# Paper

**[Actor Database Systems: A Manifesto [Shah 2017]](https://arxiv.org/pdf/1707.06507.pdf)**
* Overview and tenets of actor DB systems

**[Anna: A KVS For Any Scale [Wu 2018]](http://db.cs.berkeley.edu/jmh/papers/anna_ieee18.pdf)**
* HN: [https://news.ycombinator.com/item?id=16551072](https://news.ycombinator.com/item?id=16551072)

**[Indexing in an Actor-Oriented Database [Bernstein 2017]](http://cidrdb.org/cidr2017/papers/p29-bernstein-cidr17.pdf)**
* This paper discusses an implementation of an actor indexing feature for Orleans by using actors on top of Orleans itself. This is a useful design pattern, since many types of functionality can be directly encoded through actors, thus creating database abstractions without having to change the internals of Orleans. The preliminary code is available at: [https://github.com/OrleansContrib/Orleans.Indexing](https://github.com/OrleansContrib/Orleans.Indexing)
* [Conference Slides](http://cidrdb.org/cidr2017/slides/p29-bernstein-cidr17-slides.pdf)

**[Transactions for Distributed Actors in the Cloud [Eldeeb 2016]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/10/EldeebBernstein-TransactionalActors-MSR-TR-1.pdf)**

**[Reactors: A Case for Predictable, Virtualized Actor Database Systems [Shah 2018]](http://www.diku.dk/~vmarcos/pubs/SS18-reactdb.pdf)**

**[Geo-Distribution of Actor-Based Services [Bernstein 2017]](http://delivery.acm.org/10.1145/3140000/3133931/oopsla17-oopsla74.pdf?ip=141.89.217.179&id=3133931&acc=OA&key=2BA2C432AB83DA15%2E1F4E6143780147C9%2E4D4702B0C3E38B35%2EC1E31BC46E58D5B8&__acm__=1524525968_721522223823c75215fe1f21824fc199)**
* This paper discusses a geo-replication model for Orleans. The feature is being integrated into Orleans: [https://github.com/dotnet/orleans/issues/948](https://github.com/dotnet/orleans/issues/948). In the issue discussion, you can also find links to early branches.


# Projects

**[JustinDB](https://github.com/justin-db/JustinDB)**
* Distributed Key-Value Storage built on top of Scala/Akka

**[Blog: Actorbase or "the persistence chaos"](http://rcardin.github.io/database/actor-model/reactive/akka/scala/2016/02/07/actorbase-or-the-persistence-chaos.html)**
* Github Projects: [rcardin/actorbase](https://github.com/rcardin/actorbase), [SweeneyThreads/ActorbaseSummary](https://github.com/SweeneyThreads/ActorbaseSummary), [ScalateKids/Actorbase](https://github.com/ScalateKids/Actorbase)

**[AkkaDynoDB](https://github.com/pamu/AkkaDynoDB)**
* Dynamo like distributed database built using Akka Cluster

**[ActorDB](https://github.com/biokoda/actordb)**
* SQL DB, one table per actor

# Other

**Transactions in Orleons**
* [http://dotnet.github.io/orleans/Documentation/2.0/Transactions.html](http://dotnet.github.io/orleans/Documentation/2.0/Transactions.html) (tech report: [https://www.microsoft.com/en-us/research/publication/transactions-distributed-actors-cloud-2/](https://www.microsoft.com/en-us/research/publication/transactions-distributed-actors-cloud-2/))

**[Raft Consensus Protocol](https://raft.github.io/)**
