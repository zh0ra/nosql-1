# Technologie NoSQL

Terminarz rozliczania się z [zadań](http://wbzyl.inf.ug.edu.pl/nosql/zadania):

| zadanie |                      | stacjonarne | niestacjonarne |
|---------|--------------------- |-------------|----------------|
| 1.      | Neo4j                | 22.10.2015  | 24.10.2015     |
| 2       | EDA                  | 19.11.2015  | 27.11.2015     |
| 3.      | Aggregation Pipeline | 17.12.2015  |  8.01.2016     |
| 4.      | MapReduce            | 14.01.2016  |  8.01.2016     |

*Uwaga:* Za nierozliczenie się z zadania w terminie ocena zostanie
obniżona o jeden stopień.


## Zaliczenie i Egzamin

> A good demo is disproportionately valuable in big data science.<br>
> — [Storytelling](http://en.wikipedia.org/wiki/Storytelling)

Link do **prywatnego** repozytorium z rozwiązaniami zadań należy wpisać odpowiednio
w plikach [Zaliczenie.md](Zaliczenie.md) i [Egzamin.md](Egzamin.md)
w jednym wierszu według schematu:

    1. [Nazwisko, Imię](link do prywatnego repo z rozwiązaniami zadań)


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
   [**Markdown**](http://daringfireball.net/projects/markdown/syntax), or
   [**AsciiDoc**](http://asciidoctor.org)
   to create reports for analysis and presentation output products.

Plus two more rules:

1. Record all intermediate results, when possible in standardized formats.
1. Connect textual statements to underlying results.
