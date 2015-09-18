# Technologie NoSQL

TODO: Osobne tabelki dla stacjonarnych i niestacjonarnych.

Terminy rozliczania się z [zadań](http://wbzyl.inf.ug.edu.pl/nosql/zadania):

| zadanie |                      | termin stacjonarne |
|---------|--------------------- |------------|
| 0.      | Neo4j                | 25.10.2014 |
| 1 a-c   | EDA                  | 15.11.2014 |
| 1 d.    | GeoJSON              | 29.11.2014 |
| 2.      | Aggregation Pipeline |  6.12.2014 |
| 3*.     | MapReduce            | 10.01.2015 |


## Zaliczenie

Dane należy wpisać w pliku [Zaliczenie.md](Zaliczenie.md) według schematu:

    1. [Nazwisko, Imię](link do repo z zadaniem **Neo4j**).
       [Tytuł 1](link do repo z zadaniem **EDA** + **GeoJSON**),
       [Tytuł 2](link do repo z zadaniem **Agregacje**).


## Egzamin

> A good demo is disproportionately valuable in big data science.<br>
> — [Storytelling](http://en.wikipedia.org/wiki/Storytelling)

Dane należy wpisać według schematu (całość w jednym wierszu):

    1. Nazwisko, Imię. [Tytuł](link do repo z zadaniem 3).


## Simple Rules for Reproducible Computations

Provide public access to scripts, runs, and results:

1. Version control all custom scripts:
  - avoid writing code
  - **write thin scripts** and use standard tools and use standard UNIX
    commands to chain things together.
1. Avoid manual data manipulation steps:
  - use a build system, for example [**make**](http://bost.ocks.org/mike/make/),
    and have all results produced automatically by build targets
  - if it’s not automated, it’s not part of the project,
    i.e. have an idea for a graph or an analysis?
    automate its generation
1. Use a markup, for example
   [**Markdown**](http://daringfireball.net/projects/markdown/syntax),
   to create reports for analysis and presentation output products.

Plus two more rules:

1. Record all intermediate results, when possible in standardized formats.
1. Connect textual statements to underlying results.
