# Awesome Deduction [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome deductive databases.


## Contents

- [Deductive Database](#deductive-database)
- [Datalog](#datalog)
    - [DES: Datalog Educational System](#des-datalog-educational-system)
    - [IRIS: Integrated Rule Inference System](#iris-integrated-rule-inference-system)
    - [MITRE Datalog](#mitre-datalog)
    - [OCaml Datalog](#ocaml-datalog)
    - [pyDatalog](#pydatalog)
    - [Datomic](#datomic)
    - [Dedalus](dedalus)
- [Online](#online)

## Deductive Database
[Deductive databases](https://en.wikipedia.org/wiki/Deductive_database) combine logical programming with relational databases, and are capable of inferring new information from data stored in the database [memory banks](http://www.imdb.com/character/ch0011083/quotes); wherein multiplicative deductions are as elementary as Holmesian deduction, and are only bottlenecked by available storage capacity. Deductive databases can also be used as a form of data compression; by reverse querying.

## Datalog
[Datalog](http://en.wikipedia.org/wiki/Datalog) is a turing-incomplete subset of Prolog, used as a query language for deductive databases.

### DES: Datalog Educational System
[DES](https://sourceforge.net/projects/des/) is a cross-platform Prolog implementation of Datalog; licensed under GPL.
* [DES: A Deductive Database System](http://www.sciencedirect.com/science/article/pii/S157106611100048X)
* [DES User's Manual](http://des.sourceforge.net/html/manual.html)
* The University of Sydney:
    * [Introduction to Deductive Databases and Datalog](http://sydney.edu.au/engineering/it/courses/info2120/lectures/02adv_Datalog.pdf)
    * [Introduction to Datalog with DES](http://sydney.edu.au/engineering/it/courses/info2120/docs/DES_Walkthrough.pdf)

### IRIS: Integrated Rule Inference System
[IRIS Reasoner](http://iris-reasoner.org/) is an extension of Datalog, written in Java.
* [API and User Guide](http://iris-reasoner.org/pages/user_guide.pdf)
* [IRIS Datalog Syntax](http://iris-reasoner.org/syntax)
* [SourceForge](https://sourceforge.net/projects/iris-reasoner/)
* [GitHub](https://github.com/NICTA/iris-reasoner)

### MITRE Datalog
[MITRE Datalog](https://sourceforge.net/projects/datalog/) is a lightweight deductive database system, written in Lua.
* [MITRE Datalog User Manual](http://datalog.sourceforge.net/datalog.html)

### OCaml Datalog
[OCaml Datalog](https://github.com/ramsdell/ocaml-datalog) is an OCaml implementation of [MITRE Datalog](#mitre-datalog).

### pyDatalog
[pyDatalog](https://sites.google.com/site/pydatalog/) is a pythonic derivation of [MITRE Datalog](#mitre-datalog).
* [pyDatalog tutorial](https://sites.google.com/site/pydatalog/Online-datalog-tutorial)
* [Bitbucket](https://bitbucket.org/pcarbonn/pydatalog/wiki/browse/)

### Datomic
[Datomic](http://datomic.com/) is a proprietary dialect of Datalog.
* [Documentation](http://docs.datomic.com/)
* [Videos](http://www.datomic.com/videos.html)
* [Training](http://www.datomic.com/training.html)
* [Learn Datalog Today](http://www.learndatalogtoday.org/)

### Dedalus
[Dedalus](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2009/EECS-2009-173.html) is a temporal extension of Datalog.

## Online
These implementations run in the web browser.
* [IRIS Demo](http://iris-reasoner.org/demo); a web-based demonstration of [IRIS Datalog](#iris-integrated-rule-inference-system).
* [Datalog.js](http://ysangkok.github.io/mitre-datalog.js/wrapper.html); a Lua wrapper for [MITRE Datalog](#mitre-datalog).
