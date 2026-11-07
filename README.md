# Neo4j Ecosystem Workspace

This repository aggregates forks of core Neo4j ecosystem projects as Git submodules under [`Chief-Strategist-J`](https://github.com/Chief-Strategist-J).

## Included Submodules & Forks

| Submodule | Forked Repository | Upstream Origin |
|---|---|---|
| `neo4j` | [Chief-Strategist-J/neo4j](https://github.com/Chief-Strategist-J/neo4j) | `neo4j/neo4j` |
| `neo4j-apoc-procedures` | [Chief-Strategist-J/neo4j-apoc-procedures](https://github.com/Chief-Strategist-J/neo4j-apoc-procedures) | `neo4j-contrib/neo4j-apoc-procedures` |
| `graph-data-science` | [Chief-Strategist-J/graph-data-science](https://github.com/Chief-Strategist-J/graph-data-science) | `neo4j/graph-data-science` |
| `neo4j-graphrag-python` | [Chief-Strategist-J/neo4j-graphrag-python](https://github.com/Chief-Strategist-J/neo4j-graphrag-python) | `neo4j/neo4j-graphrag-python` |
| `neo4j-python-driver` | [Chief-Strategist-J/neo4j-python-driver](https://github.com/Chief-Strategist-J/neo4j-python-driver) | `neo4j/neo4j-python-driver` |
| `neomodel` | [Chief-Strategist-J/neomodel](https://github.com/Chief-Strategist-J/neomodel) | `neo4j-contrib/neomodel` |
| `graphql` | [Chief-Strategist-J/graphql](https://github.com/Chief-Strategist-J/graphql) | `neo4j/graphql` |
| `neo4j-javascript-driver` | [Chief-Strategist-J/neo4j-javascript-driver](https://github.com/Chief-Strategist-J/neo4j-javascript-driver) | `neo4j/neo4j-javascript-driver` |
| `spring-data-neo4j` | [Chief-Strategist-J/spring-data-neo4j](https://github.com/Chief-Strategist-J/spring-data-neo4j) | `spring-projects/spring-data-neo4j` |
| `neo4j-spark-connector` | [Chief-Strategist-J/neo4j-spark-connector](https://github.com/Chief-Strategist-J/neo4j-spark-connector) | `neo4j-contrib/neo4j-spark-connector` |
| `neo4j-kafka-connector` | [Chief-Strategist-J/neo4j-kafka-connector](https://github.com/Chief-Strategist-J/neo4j-kafka-connector) | `neo4j/neo4j-kafka-connector` |
| `neodash` | [Chief-Strategist-J/neodash](https://github.com/Chief-Strategist-J/neodash) | `neo4j-labs/neodash` |

## Quick Start

To clone this repository and initialize all submodules at once:
```bash
git clone --recurse-submodules https://github.com/Chief-Strategist-J/neo4j-ecosystem-workspace.git
```

If you already cloned without recursion:
```bash
git submodule update --init --recursive
```
