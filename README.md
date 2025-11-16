# API-CONTROLE-DE-ESTOQUE
# 📦 Sistema de Controle de Estoque – API NestJS

Este projeto é uma API completa desenvolvida com NestJS, projetada para gerenciar produtos em estoque,
registrar movimentações (entrada e saída), consultar disponibilidade e gerar relatórios de produtos críticos.

O objetivo do sistema é ser simples, didático e organizado, servindo tanto como projeto prático quanto como
base para estudos de arquitetura backend, validação, DTOs, serviços e regras de negócio.

`==============================================================`

🚀 Funcionalidades Principais

`==============================================================`
✅ Cadastro de produtos
Criar um novo produto com código, nome, quantidade inicial, estoque mínimo e valor unitário.
Validação de duplicidade de código.
Regras de negócio para valores mínimos.

`==============================================================`
📊 Consulta de estoque
`==============================================================`
Listar todos os produtos.
Buscar produto por código.
Destacar produtos críticos (estoque abaixo do mínimo).
Calcular valor total do estoque.

`==============================================================`
➕ Registro de entrada
`==============================================================`
Adicionar quantidade ao estoque.
Registrar data/hora da movimentação.

`==============================================================`
➖ Registro de saída
`==============================================================`
Validar estoque suficiente.
Atualizar quantidade.
Avisar quando o estoque ficar abaixo do mínimo.

`==============================================================`
📉 Relatório de produtos críticos
`==============================================================`
Listar produtos com estoque abaixo do mínimo.
Ordenar por prioridade (mais críticos primeiro).
Calcular quantidade necessária para reposição.

`==============================================================`
🧱 Tecnologias Utilizadas
NestJS
TypeScript
Zod  (validações)
Prisma (opcional) ou dados em memória

`==============================================================`
📘 Regras de Negócio Implementadas
`==============================================================`
Quantidade inicial e estoque mínimo não podem ser negativos.
Código do produto deve ser único.
Saída só ocorre se houver estoque suficiente.
Toda movimentação registra data e hora.
Produtos abaixo do estoque mínimo são considerados críticos.
Relatórios retornam itens ordenados pelo nível de criticidade.

`==============================================================`

📄 Licença
Este projeto está sob a licença MIT.
Sinta-se livre para usar, modificar e distribuir

