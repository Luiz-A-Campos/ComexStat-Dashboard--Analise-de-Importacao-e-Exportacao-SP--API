# 📌 MVP - Aldo Pereira Solutions

## 🎯 Objetivo do MVP
O MVP da Sprint 3 tem como objetivo integrar e consolidar os dados de importação e exportação dos municípios do estado de São Paulo em um único ambiente de análise. A proposta é oferecer uma visão mais completa do comércio exterior, permitindo acompanhar indicadores econômicos, identificar superávits e déficits comerciais e analisar a evolução das operações ao longo do tempo.

- Qual problema resolve?
Apesar dos dashboards desenvolvidos nas sprints anteriores permitirem análises de importação e exportação separadamente, ainda faltava uma visão consolidada que facilitasse a comparação entre esses indicadores e ajudasse a compreender melhor o desempenho comercial dos municípios paulistas.

- Qual hipótese será validada?
Se os dados de exportação e importação forem apresentados de forma integrada, juntamente com indicadores de saldo comercial, superávit e déficit comercial, os usuários conseguirão realizar análises mais completas e tomar decisões com maior embasamento.

- Qual valor será entregue ao usuário final?  
O MVP entregará uma ferramenta capaz de apresentar informações consolidadas sobre comércio exterior, permitindo visualizar exportações, importações, saldo comercial, principais parceiros comerciais e evolução histórica dos indicadores de forma clara e acessível.

---

## 📝 Descrição da Solução
Nesta sprint será desenvolvido um dashboard consolidado de comércio exterior, reunindo os dados de importação e exportação trabalhados nas etapas anteriores. Além disso, serão criadas análises específicas para identificar países com superávit e déficit comercial e acompanhar a evolução das operações ao longo dos anos.

### Funcionalidades principais incluídas:

- Valor FOB de Exportação;
- Valor FOB de Importação;
- Saldo Comercial;
- Quilogramas exportados;
- Quilogramas importados;
- Total de operações de exportação;
- Total de operações de importação;
- Filtros por município, país, produto SH4, mês e ano;
- Mapa de calor dos países com superávit comercial;
- Mapa de calor dos países com déficit comercial;
- Ranking dos principais países com superávit comercial;
- Ranking dos principais países com déficit comercial;
- Gráfico de evolução das exportações e importações ao longo do tempo;
- Comparação entre exportações e importações por período.

### Limitações conhecidas

- A atualização dos dados ainda exige tratamento manual;
- Não existem projeções automáticas para cenários futuros;
- Ainda não há integração automática com fontes externas de dados.

### Escopo reduzido (somente o essencial para validar a ideia)

Nesta etapa, o foco está na integração dos dados de importação e exportação, indicadores de saldo comercial e pesagem, criação das análises de superávit e déficit comercial e gráficos comparativos.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** breve descrição, necessidades e dores atendidas  
- **Persona 2:** breve descrição, necessidades e dores atendidas  

---

## 🔑 User Stories (Backlog do MVP)
| Rank  | User Story                                                                 | Prioridade |
|-----|-----------------------------------------------------------------------------|------------|
| 1  | Como cliente, quero comparar o saldo comercial entre diferentes municípios no período de 2021 a fevereiro de 2026 para identificar quais regiões apresentam maior resiliência econômica. | Alta |
| 2  | Como cliente, quero que toda a origem dos dados e as fórmulas de cálculo (como o Saldo Comercial) estejam documentadas e versionadas, para que eu tenha total confiança de que os números apresentados no dashboard são verídicos e auditáveis. | Alta |
| 3  | Como cliente, quero filtrar as importações do vale do Paraíba por categoria de produto (NCM) e país de origem, para identificar insumos que hoje compramos de longe, mas que poderiam ser produzidos ou fornecidos localmente. | Média |
| 4 | Como cliente, quero que cada etapa da limpeza de dados realizada no Google Colab, seja salva em abas separadas no GitHub para manter um histórico de versões e evitar a perda de progresso durante o desenvolvimento. | Baixa |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | [Funcionalidade X, Y]                        | Concluído|
| 02     | [Funcionalidade Z]                           | Em andamento |

---

## 📊 Critérios de Aceitação

- O MVP deve permitir que o usuário visualize e compare dados de exportação e importação por município, país, produto, mês e ano.

- O sistema deve registrar e apresentar automaticamente os indicadores de Valor FOB de Exportação, Valor FOB de Importação, Saldo Comercial, peso líquido movimentado e quantidade de operações.

- Métricas coletadas:
  - Tempo de carregamento dos dashboards;
  - Quantidade de filtros;
  - Tempo médio de navegação nos dashboards;
  - Quantidade de análises disponíveis;

---

## 📈 Métricas de Validação

### Número de usuários que testaram o MVP


### Feedback qualitativo (positivo/negativo)

Os testes realizados mostraram resultados positivos quanto à organização dos dados, facilidade de navegação e clareza dos indicadores. Os usuários destacaram a praticidade em visualizar informações unidas em um único dashboard. Como pontos de melhoria, foi sugerido a visualização de comparações mais avançadas e detalhadas.

### Indicadores de negócio

- Redução do tempo necessário para análise dos dados;
- Aumento da eficiência na tomada de decisão;
- Melhor interpretação dos indicadores econômicos;
- Identificação mais rápida de oportunidades comerciais;
- Maior acessibilidade aos dados públicos de comércio exterior.

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
