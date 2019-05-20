## SPARQL Tutorial

The objective of this SPARQL tutorial is to give a fast course in SPARQL. The tutorial covers the major features of the query language through examples but does not aim to be complete.
本教程的目的是提供一个SPARQL快速课程。本教程通过示例介绍了查询语言的主要功能, 但其目的并不在于完整。

如果您正在寻找 SPARQL 和Jena的简短介绍, 请试读[SPARQL 搜索 RDF 数据](https://developer.ibm.com/articles/j-sparql/)。如果您希望在代码中执行 SPARQL 查询, 并且已经知道 SPARQL, 那么您可能适合阅读 [ARQ 文档](http://jena.apache.org/documentation/query/index.html)。


SPARQL 是一种用于访问 RDF 的查询语言和协议, 由 W3C RDF 数据访问工作组设计。

SPARQL 作为一种查询语言, 它是 "面向数据" 的, 因为它只查询模型中包含的信息;查询语言本身没有推理。 当然, Jena 模型可能是 "智能的", 因为它可以根据需求创建出特定的三元组（triples）, 例如通过 OWL 推理。 SPARQL 除了以查询的形式对应用程序所需内容进行描述之外, 不会执行任何其他操作, 而是以一组绑定（bindings）或 RDF 图（RDF graph）的形式返回该信息。


## SPARQL tutorial

1. [Preliminaries: data!](https://jena.apache.org/tutorials/sparql_data.html)
1. Executing a simple query
1. Basic patterns
1. Value constraints
1. Optional information
1. Alternatives
1. Named Graphs
1. Results

## Other Material

* The SPARQL query language definition document itself contains many examples.
* Search RDF data with SPARQL (by Phil McCarthy) - article published on IBM developer works about SPARQL and Jena.
* SPARQL reference card (by Dave Beckett)

Detailed ARQ documentation

