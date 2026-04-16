# Projeto: Fundamentos do Databricks com NotebookLM

## Contexto e Objetivo

Este projeto tem como objetivo estudar a plataforma Databricks utilizando o NotebookLM como ferramenta de apoio ao aprendizado.

O foco foi entender como a arquitetura Lakehouse integra engenharia de dados, análise e inteligência artificial em um único ambiente.

Objetivos:
- Compreender os principais componentes do Databricks
- Entender como garantir performance, governança e confiabilidade de dados
- Praticar a construção de prompts mais eficientes
- Consolidar o aprendizado em um material reutilizável
---
## Curadoria de Fontes

- https://b-eye.com/blog/databricks-photon-performance-optimization-guide/
- https://www.fivetran.com/learn/what-is-delta-lake
- https://www.youtube.com/watch?v=XOSuR8g2SfQ
- https://procogia.com/databricks-unity-catalog/
- https://www.conduktor.io/glossary/delta-lake-transaction-log-how-it-works
- https://carreiradados.com.br/o-guia-definitivo-do-databricks/
---

## Engenharia de Prompts

### Prompt inicial
"Quais são os principais componentes do Databricks?"

Resultado: resposta genérica.

### Ajuste
"Explique os principais componentes do Databricks com foco em performance, governança e confiabilidade"

Resultado: resposta mais estruturada e útil.

---

### Prompt inicial
"Como o Delta Lake garante confiabilidade?"

Resultado: explicação superficial.

### Ajuste
"Explique como o Delta Lake garante confiabilidade incluindo ACID, transaction log e time travel"

Resultado: resposta mais completa.

---

### Dificuldades

- Respostas muito amplas no início
- Necessidade de adicionar contexto técnico nos prompts
- Melhor resultado ao especificar objetivo e cenário

---

## Miniguia de Estudo

### Visão Geral

O Databricks é uma plataforma baseada na arquitetura Lakehouse, que combina características de data lakes e data warehouses.

Isso permite trabalhar com engenharia de dados, análise e machine learning no mesmo ambiente.

---

### Componentes principais

**Photon**
Motor de execução otimizado, com foco em performance para consultas SQL e processamento de dados.

**Delta Lake**
Camada que adiciona confiabilidade aos dados, com suporte a transações ACID, versionamento e histórico.

**Unity Catalog**
Responsável pela governança, controle de acesso e rastreamento de dados.

Esses pontos foram reforçados no material estudado :contentReference[oaicite:0]{index=0}

---

### Benefícios

- Integração de diferentes áreas de dados em uma única plataforma
- Melhor performance em processamento
- Maior confiabilidade dos dados
- Governança centralizada

---

### Glossário

- Lakehouse: combinação de data lake e data warehouse
- ACID: conjunto de propriedades para garantir integridade dos dados
- Photon: motor de execução do Databricks
- Delta Lake: camada de confiabilidade dos dados
- Unity Catalog: sistema de governança
- Time Travel: acesso a versões anteriores dos dados
- Lineage: rastreamento da origem dos dados

---

### Prompts reutilizáveis

- Explique [tema] com foco em performance e governança
- Quais problemas [tecnologia] resolve
- Compare [tecnologia A] e [tecnologia B]
- Dê exemplos práticos de uso
- Quais são as limitações de [tecnologia]

---

## Conclusão

O uso do NotebookLM ajudou a estruturar melhor o aprendizado, permitindo transformar conteúdo técnico em conhecimento organizado.

O Databricks se destaca por unificar processamento, governança e confiabilidade em uma única plataforma, sendo uma solução relevante para ambientes modernos de dados.
