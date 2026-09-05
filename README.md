# Algoritmos com Grafos em Java

> Busca em largura (BFS) e busca em profundidade (DFS), nas versões recursiva e com pilha, sobre um grafo de vértices ligados por lista de adjacência.

![status](https://img.shields.io/badge/status-concluído-success) ![java](https://img.shields.io/badge/Java-8-blue)

## Sobre
Exercício de estudo de algoritmos em grafos (2017). O grafo é montado em memória a partir de objetos `Vertice`, cada um com sua lista de vizinhos, e percorrido por BFS e DFS imprimindo a ordem de visita.

## Stack
- Java 8, sem dependências externas
- Projeto no formato Eclipse

## Estrutura de pastas
```text
src/
├── bfs/BFS.java          busca em largura com fila
├── dfs/DFS.java          busca em profundidade recursiva e com pilha
├── entity/Vertice.java   vértice com flag de visitado e vizinhança
├── entity/Cidade.java    dado armazenado no vértice
├── main/Main.java        monta um grafo de exemplo e executa as buscas
└── test/TestesGrafos.java casos de teste
```

## Como executar
```bash
javac -d bin $(find src -name "*.java")
java -cp bin main.Main
```

## Status
Concluído. Material de estudo; não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
