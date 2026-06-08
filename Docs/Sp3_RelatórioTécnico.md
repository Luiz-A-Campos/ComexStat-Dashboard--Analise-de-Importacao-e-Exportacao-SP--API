# Relatório Técnico Sprint 3

## 2. Definição do Objetivo do MVP 3

O MVP 3 foi definido como uma evolução da solução desenvolvida nas sprints anteriores, com foco na integração dos dados de importação e exportação em um único ambiente analítico.

O objetivo do MVP 3 é consolidar as informações de comércio exterior dos municípios do estado de São Paulo em dashboards integrados, permitindo análises comparativas entre importações e exportações, cálculo do saldo comercial e identificação de cenários de superávit e déficit comercial.

A definição desse objetivo foi realizada com base na necessidade de oferecer uma visão mais completa do comércio exterior paulista, ampliando a capacidade analítica da plataforma e facilitando a interpretação dos indicadores econômicos.

---

## 3. Definição do Problema

O problema foi definido a partir da análise das limitações identificadas nas sprints anteriores.

Embora os dashboards de importação e exportação apresentassem informações relevantes, os dados permaneciam separados, dificultando análises integradas sobre o desempenho comercial dos municípios e limitando a identificação de tendências relacionadas à balança comercial.

A ausência de uma visão consolidada dificultava a comparação entre exportações e importações, reduzindo o potencial de apoio à tomada de decisão.

A definição desse problema orientou diretamente o escopo do MVP 3, concentrando esforços na integração dos dados e no desenvolvimento de indicadores comparativos.

---

## 4. Definição da Hipótese

A hipótese da Sprint 3 foi definida como:

>  Se os dados de exportação e importação forem apresentados de forma integrada, juntamente com indicadores de saldo comercial, superávit e déficit comercial, os usuários conseguirão realizar análises mais completas e tomar decisões com maior embasamento.

Essa hipótese foi construída considerando que a integração das informações aumenta a capacidade de interpretação dos dados e reduz o tempo necessário para análises comparativas.

---

## 5. Definição do Valor Entregue

O valor do MVP 3 foi definido com foco na ampliação da capacidade analítica da plataforma.

O MVP entregará uma ferramenta capaz de apresentar informações consolidadas sobre comércio exterior, permitindo visualizar exportações, importações, saldo comercial, indicadores potenciais e evolução histórica dos indicadores de forma clara e acessível.

### Funcionalidades entregues

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

A definição do valor foi baseada na necessidade de fornecer uma visão consolidada do comércio exterior, permitindo análises mais estratégicas e detalhadas.

---

## 6. Definição da Solução Técnica

A solução foi definida com base em seis pilares principais:

- Integração dos dados de importação e exportação;
- Implementação do indicador de saldo comercial;
- Criação de rankings de superávit e déficit comercial;
- Desenvolvimento de análises históricas comparativas;
- Ampliação dos filtros dinâmicos;

Para o tratamento dos dados foi utilizado o Google Colab, devido à sua integração com Python e facilidade para manipulação dos conjuntos de dados do COMEXSTAT.

### Processo de tratamento dos dados

- Importação dos dados do COMEXSTAT;
- Padronização das bases de importação e exportação;
- Limpeza dos dados;
- Validação dos registros;
- Integração das tabelas;
- Cálculo do saldo comercial;
- Organização dos dados para consumo pelo Power BI.

Após o tratamento, os dados foram exportados para utilização nos dashboards desenvolvidos.

---

## 7. Estruturação das Tabelas

As tabelas foram estruturadas para suportar análises comparativas e indicadores de desempenho comercial.

Foi criada uma base integrada contendo:

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

A definição dessas colunas foi baseada nas necessidades identificadas nas histórias de usuário e nos objetivos do MVP 3.

---

## 8. Desenvolvimento do Dashboard

O dashboard foi desenvolvido no Power BI com foco em integração, comparabilidade e usabilidade.

### Funcionalidades implementadas

- Indicadores de exportação;
- Indicadores de importação;
- Indicador de saldo comercial;
- Gráficos comparativos entre importações e exportações;
- Evolução histórica do comércio exterior;
- Ranking de países com superávit comercial;
- Ranking de países com déficit comercial;
- Mapas de análise geográfica;
- Segmentações por município;
- Segmentações por país;
- Segmentações por produto;
- Segmentações por período.

A estrutura do dashboard foi desenvolvida para validar a hipótese da Sprint 3 e ampliar a capacidade analítica da plataforma.

---

## 9. Definição das Personas

As personas foram mantidas devido à sua aderência aos objetivos do projeto.

### Analista Institucional de Dados (CADI)

Responsável pela análise do desempenho econômico dos municípios. Necessita de indicadores consolidados e visualizações que facilitem a comparação entre diferentes regiões.

### Estudante/Pesquisador

Utiliza os dados para fins acadêmicos e estudos econômicos. Necessita de dados estruturados, confiáveis e facilmente acessíveis.

### Analista de Logística

Responsável por avaliar fluxos comerciais e movimentação de mercadorias. Necessita compreender padrões de importação, exportação e desempenho logístico.

A definição das personas continuou orientando as funcionalidades desenvolvidas no MVP 3.

---

## 10. Definição das Histórias de Usuário

As histórias de usuário foram definidas utilizando a estrutura ágil:

> "Como [usuário], quero [funcionalidade], para [objetivo]"

A priorização foi realizada de acordo com a relevância para validação da hipótese da Sprint 3.

### Histórias de Alta Prioridade

Como cliente, quero comparar o saldo comercial entre diferentes municípios no período de 2021 a fevereiro de 2026 para identificar quais regiões apresentam maior resiliência econômica.

Como cliente, quero que toda a origem dos dados e as fórmulas de cálculo (como o Saldo Comercial) estejam documentadas e versionadas, para que eu tenha total confiança de que os números apresentados no dashboard são verídicos e auditáveis.

### Histórias de Média Prioridade

Como cliente, quero filtrar as importações do vale do Paraíba por categoria de produto (NCM) e país de origem, para identificar insumos que hoje compramos de longe, mas que poderiam ser produzidos ou fornecidos localmente.

### Histórias de Baixa Prioridade

Como cliente, quero que cada etapa da limpeza de dados realizada no Google Colab, seja salva em abas separadas no GitHub para manter um histórico de versões e evitar a perda de progresso durante o desenvolvimento.

---

## 11. Definição dos Critérios de Aceitação

Os critérios de aceitação foram definidos para garantir que as funcionalidades entregues atendessem aos objetivos do MVP.

### Critérios definidos

- O MVP deve permitir que o usuário visualize e compare dados de exportação e importação por município, país, produto, mês e ano.

- O sistema deve registrar e apresentar automaticamente os indicadores de Valor FOB de Exportação, Valor FOB de Importação, Saldo Comercial, peso líquido movimentado e quantidade de operações.

### Métricas coletadas

  - Tempo de carregamento dos dashboards;
  - Quantidade de filtros;
  - Tempo médio de navegação nos dashboards;
  - Quantidade de análises disponíveis;

Esses critérios foram definidos para validar a hipótese proposta para a Sprint 3.

---

## 12. Execução da Sprint 3

A Sprint 3 foi executada seguindo as etapas do processo ágil:

- Refinamento do backlog;
- Priorização das histórias de usuário;
- Integração das bases de dados;
- Tratamento e validação das informações;
- Desenvolvimento dos dashboards;
- Testes internos;

### Principais entregas

- Base integrada de importação e exportação;
- Cálculo automatizado do saldo comercial;
- Dashboard consolidado no Power BI;
- Rankings de superávit e déficit comercial;

---

## 13. Métricas de Validação

A validação do MVP 3 foi realizada por meio de testes internos conduzidos pela equipe.

### Número de usuários que testaram

**2 usuários**

### Participantes dos testes

- Luiz Augusto (Scrum Master);
- Rita Carolina (Team Member).

### Feedbacks recebidos

- Maior facilidade na análise comparativa;
- Melhor compreensão do desempenho econômico dos municípios;
- Clareza das visualizações;
- Necessidade futura de novas funcionalidades analíticas.

---

## 14. Resultados Obtidos

Os principais resultados da Sprint 3 foram:

- Integração completa dos dados de importação e exportação;
- Implementação do indicador de saldo comercial;
- Melhoria da análise comparativa entre municípios;
- Identificação de cenários de superávit e déficit comercial;
- Maior eficiência na interpretação dos dados;
- Redução do tempo necessário para análises econômicas;
- Ampliação da capacidade de apoio à tomada de decisão;
- Maior transparência dos cálculos e fontes utilizadas.

---

## 15. Limitações Identificadas

As limitações identificadas no MVP 3 foram:

- A atualização dos dados ainda exige tratamento manual;
- Não existem projeções automáticas para cenários futuros;
- Ainda não há integração automática com fontes externas de dados.

---

## 16. Conclusão da Sprint 3

A Sprint 3 cumpriu seu objetivo ao consolidar as informações de importação e exportação em uma única solução analítica.

Foi possível validar que a integração dos dados e a utilização do saldo comercial ampliam significativamente a capacidade de análise do comércio exterior dos municípios do estado de São Paulo.

Os resultados obtidos demonstraram que a plataforma evoluiu para um nível mais avançado de análise, oferecendo informações mais completas para pesquisadores, analistas e gestores.

A partir desta etapa, o projeto poderá evoluir para novas funcionalidades, como automação da coleta de dados, integração web e utilização de técnicas de análise preditiva para apoiar o planejamento econômico e logístico.
