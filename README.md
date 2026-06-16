# Busca Gulosa (Greedy Search)

Este repositório contém uma implementação simples do algoritmo de **busca gulosa** (Greedy Search) em Python para busca em grafos.

## O que é Busca Gulosa?

A busca gulosa é um algoritmo de busca heurística que, em cada passo, escolhe expandir o nó que parece estar mais próximo do objetivo, baseado em uma função heurística. Diferente do A*, a busca gulosa não considera o custo acumulado do caminho, apenas a estimativa local para o objetivo.

## Estrutura do Repositório


- `src/greedy_search.py`: Código principal da implementação da busca gulosa.
- `examples/example_graph.txt`: Exemplo de grafo (opcional).
- `README.md`: Este arquivo.

## Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Busca-gulosa.git
   cd Busca-gulosa
python src/greedy_search.py
Caminho encontrado pela busca gulosa: A -> C -> F
