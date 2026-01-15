# Controle de Estoque Interativo - Excel

Este projeto consiste em uma planilha avançada de **Controle de Estoque** desenvolvida em Microsoft Excel, utilizando recursos visuais, macros (VBA) e fórmulas dinâmicas para facilitar a gestão de ativos e insumos.

## 🖥 Telas do Sistema

### 1. Painel de Movimentação (Início)
Esta é a interface principal de operação, focada na agilidade do dia a dia.
* **Seleção de Produto:** Menu lateral à esquerda para escolha rápida do item.
* **Indicadores Rápidos:** Cartões que mostram a quantidade atual "No Estoque" e pedidos "Na Fila".
* **Ações de Entrada/Saída:** Campos para digitar a quantidade e descrição, com botões estilizados para registrar a movimentação instantaneamente.
* **Identificação Visual:** Exibição da foto do produto selecionado para evitar erros de lançamento.

### 2. Controle de Entradas e Saídas (Logs)
Uma visão tabular detalhada de todo o histórico de movimentações.
* **Rastreabilidade:** Registro de Data, Tipo de Operação (Entrada, Saída, Fila), Nome do Produto, Quantidade e o Número do Chamado/Ticket associado.
* **Identificação de Usuário:** Coluna dedicada para saber quem realizou a movimentação ou quem é o solicitante.
* **Filtros Dinâmicos:** Segmentação de dados à direita para filtrar rapidamente por tipo de operação.

### 3. Visão Geral do Estoque (Status)
Uma tela de inventário em tempo real com alertas inteligentes.
* **Métricas Consolidadas:** Tabela com Produto, total de Entradas, Saídas, Saldo atual e itens Pendentes (Fila).
* **Gestão de Compras (Alertas):** Coluna de "ALERTA" que indica automaticamente se o status está "OK" ou se é necessário "COMPRAR" com base nos níveis de estoque.
* **Catálogo Visual:** Inclui miniaturas das fotos de cada item para facilitar a conferência física.

### 4. Gestão de Kits (On-boarding)
Interface especializada para a saída de múltiplos itens simultâneos, ideal para processos de contratação (On-boarding).
* **Seleção por Checkbox:** Permite selecionar vários itens (ex: Mochila, Headset, Carregador) de uma só vez.
* **Saída em Lote:** Botão dedicado para dar baixa em todos os itens do kit com um único clique, otimizando o tempo operacional.

### 5. Melhorias e Log de Desenvolvimento
Uma tela de governança para o desenvolvimento da própria ferramenta.
* **Roadmap:** Lista de solicitações de melhoria, novas funcionalidades (como controle de estoque mínimo e bloqueio de estoque negativo) e seu respectivo status de implementação.

---

## 🚀 Tecnologias Utilizadas
* **Microsoft Excel:** Estrutura de dados e interface.
* **Fórmulas Avançadas:** Para cálculos de saldo e alertas automáticos.
* **Macros/VBA:** Para automação dos botões de entrada, saída e navegação entre telas.
* **Segmentação de Dados:** Para filtros rápidos e intuitivos.

---

*Nota: Certifique-se de habilitar as Macros ao abrir o arquivo para o funcionamento completo de todas as telas.*
