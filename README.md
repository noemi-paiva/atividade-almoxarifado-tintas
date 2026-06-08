# atividade-almoxarifado-tintas

# 🏭 Atividade Prática – Desenvolvimento de Sistemas
# Sistema de Gestão de Almoxarifado de Tintas

## Apresentação

Uma empresa do setor industrial utiliza um almoxarifado para armazenar tintas empregadas em diferentes etapas de seu processo produtivo.
Nos últimos meses, o crescimento da operação aumentou significativamente a quantidade de produtos armazenados e movimentados diariamente. Como consequência, foram identificados problemas relacionados ao controle de estoque, rastreabilidade das movimentações, organização dos dados e experiência de utilização do sistema atual.
Com o objetivo de melhorar o processo de gestão, foi disponibilizada uma aplicação web que necessita de correções, melhorias e novas funcionalidades.
Sua missão será analisar a solução existente e evoluí-la de acordo com as necessidades apresentadas.

# 🎯 Objetivo da Atividade

Esta atividade tem como finalidade avaliar sua capacidade de:
- Analisar sistemas existentes;
- Compreender regras de negócio;
- Identificar oportunidades de melhoria;
- Implementar novas funcionalidades;
- Organizar e estruturar código;
- Trabalhar com banco de dados;
- Aplicar boas práticas de desenvolvimento;
- Realizar testes e validações;
- Utilizar versionamento de código.

# 🏢 Cenário da Empresa

A empresa possui um almoxarifado responsável pelo armazenamento de tintas utilizadas nos setores de produção.
Atualmente, o sistema permite apenas operações básicas relacionadas ao cadastro de produtos e registro de entradas.
Entretanto, a equipe de gestão identificou a necessidade de ampliar os recursos disponíveis para melhorar o controle do estoque e fornecer informações mais confiáveis para tomada de decisão.
Você foi designado para atuar como desenvolvedor responsável pela evolução desta aplicação.

# 📦 Regras de Negócio
## Produtos
Cada produto representa uma tinta armazenada no almoxarifado.
As informações mínimas esperadas são:
- Código do produto
- Nome da tinta
- Fabricante
- Cor
- Tipo
- Unidade de medida
- Quantidade em estoque

## Movimentações
Toda alteração no estoque deverá ser registrada.
As movimentações podem ser classificadas como:

### Entrada
Utilizada quando novos produtos chegam ao almoxarifado.
Exemplos:
- Compra de materiais
- Reposição de estoque
- Devolução de materiais

### Saída
Utilizada quando produtos deixam o estoque.
Exemplos:
- Consumo na produção
- Transferência para outro setor
- Perdas ou descartes


# 🔍 Situação Atual do Sistema
O sistema disponibilizado apresenta funcionalidades básicas já implementadas.

### Disponível
- Cadastro de produtos
- Edição de produtos
- Exclusão de produtos
- Listagem de produtos
- Registro de entrada de estoque

### Limitações Identificadas
- Interface simples
- Ausência de filtros
- Ausência de paginação
- Ausência de histórico detalhado
- Falta de validações
- Estrutura de código que pode ser melhorada
- Ausência de indicadores de estoque

# 🚀 Desafios Propostos
Durante a atividade, analise a aplicação e implemente melhorias que agreguem valor ao sistema.

## Controle de Produtos
Implementar recursos como:
- Pesquisa por nome
- Filtro por fabricante
- Filtro por tipo de tinta
- Paginação de resultados

## Controle de Movimentações
Implementar:
- Registro de saídas
- Histórico completo de movimentações
- Atualização automática do estoque
- Consulta de movimentações por período

## Interface do Sistema
Melhorar a experiência do usuário através de:
- Organização visual
- Responsividade
- Padronização de componentes
- Melhor navegação entre telas

## Qualidade do Código
Avaliar a estrutura atual da aplicação e realizar melhorias quando necessário.
Exemplos:
- Reutilização de código
- Organização de arquivos
- Clareza na implementação
- Redução de duplicidade

# 📊 Funcionalidades Desejáveis
Além dos requisitos principais, poderão ser implementados recursos adicionais que agreguem valor à solução.
Exemplos:
- Dashboard com indicadores
- Alertas de estoque baixo
- Relatórios
- Exportação de dados
- Controle de usuários

# 🧪 Testes
Após a implementação das melhorias, realize testes para validar o funcionamento da aplicação.
Sugestões de cenários:
| Cenário | Resultado Esperado |
|----------|-------------------|
| Cadastro de produto | Produto salvo com sucesso |
| Edição de produto | Dados atualizados |
| Entrada de estoque | Quantidade incrementada |
| Saída de estoque | Quantidade reduzida |
| Pesquisa de produto | Resultados filtrados |

# 📂 Estrutura Inicial do Projeto

atividade-almoxarifado-tintas/
│
├── assets/
│   ├── css/
│   ├── js/
│   └── img/
│
├── config/
│
├── includes/
│
├── pages/
│
├── infra/
│
├── docs/
│
├── index.php
└── README.md

# 💾 Banco de Dados
O script de criação do banco de dados encontra-se na pasta:

```text
infra/
```
Realize a importação antes de executar o sistema.


# 🔧 Ambiente de Desenvolvimento
Tecnologias utilizadas:
- PHP
- HTML
- CSS
- JavaScript
- MySQL
- Git

Servidor recomendado:
- XAMPP

# 📤 Entrega Esperada
Ao final da atividade, espera-se que o sistema apresente melhorias funcionais e visuais, demonstrando a aplicação dos conhecimentos adquiridos ao longo do curso.


# 🏁 Boa atividade!

Analise a situação proposta, planeje suas ações, implemente as melhorias necessárias e registre sua evolução durante o desenvolvimento.

Prof.ª Noemi Paiva
