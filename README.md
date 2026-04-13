# Sistema de Busca Otimizado para Catálogo de Produtos - MegaStore

# MegaStore Search System

Sistema de busca otimizado para e-commerce desenvolvido em Rust, com foco em alta performance, escalabilidade e precisão na recuperação de produtos.

---

## Sobre o Projeto

A MegaStore enfrentava problemas de lentidão e imprecisão em seu sistema de busca devido ao uso de estruturas de dados ineficientes e ausência de indexação adequada.  

Este projeto propõe uma solução baseada em estruturas de dados otimizadas e algoritmos eficientes para garantir buscas rápidas e resultados relevantes, mesmo em cenários com grandes volumes de dados.

---

## Objetivos

- Melhorar a performance do sistema de busca  
- Reduzir o tempo de resposta  
- Aumentar a precisão dos resultados  
- Garantir escalabilidade para milhões de produtos  

---

## Arquitetura do Sistema

O sistema foi dividido em módulos:

- **Indexação:** responsável por organizar os dados usando HashMap  
- **Busca:** realiza consultas rápidas com complexidade média O(1)  
- **Recomendação:** utiliza grafos para sugerir produtos relacionados  
- **Ordenação:** organiza os resultados por relevância  

---

## Tecnologias Utilizadas

- Rust (linguagem principal)  
- Cargo (gerenciamento de projeto)  
- Estruturas da biblioteca padrão (`HashMap`, `Vec`)  

---

## Estruturas de Dados Utilizadas

| Estrutura | Aplicação |
|----------|--------|
| HashMap | Busca rápida de produtos |
| Vec | Armazenamento de listas |
| Grafo | Recomendação de produtos |

