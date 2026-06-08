# ✅ Critérios de Validação — Sprint 3

## User Story 1

**"Como cliente, quero comparar o saldo comercial entre diferentes municípios no período de 2021 a fevereiro de 2026 para identificar quais regiões apresentam maior resiliência econômica."**

### Critérios de validação:

- O sistema deve permitir a seleção de diferentes municípios do estado de São Paulo para comparação.
- O sistema deve apresentar os valores de exportação, importação e saldo comercial dos municípios selecionados.
- O sistema deve permitir a análise dos dados entre janeiro de 2021 e fevereiro de 2026.
- O sistema deve exibir gráficos e indicadores que facilitem a identificação de municípios com superávit ou déficit comercial.

---

## User Story 2

**"Como cliente, quero que toda a origem dos dados e as fórmulas de cálculo (como o Saldo Comercial) estejam documentadas e versionadas, para que eu tenha total confiança de que os números apresentados no dashboard são verídicos e auditáveis."**

### Critérios de validação:

- O projeto deve conter documentação identificando as fontes de dados utilizadas.
- O cálculo do Saldo Comercial e dos demais indicadores deve estar documentado no relatório ou repositório do projeto.
- Os arquivos utilizados no tratamento e análise dos dados devem estar versionados no GitHub.
- A documentação deve permitir que outro usuário compreenda a origem dos dados e reproduza os cálculos realizados.

---

## User Story 3

**"Como cliente, quero filtrar as importações do Vale do Paraíba por categoria de produto (NCM) e país de origem, para identificar insumos que hoje compramos de longe, mas que poderiam ser produzidos ou fornecidos localmente."**

### Critérios de validação:

- O sistema deve permitir filtrar os dados de importação por código NCM.
- O sistema deve permitir filtrar os dados por país de origem dos produtos.
- O sistema deve permitir a análise dos municípios pertencentes à região do Vale do Paraíba.
- O sistema deve atualizar automaticamente os indicadores e gráficos conforme os filtros aplicados.

---

## User Story 4

**"Como cliente, quero que cada etapa da limpeza de dados realizada no Google Colab seja salva em abas separadas no GitHub para manter um histórico de versões e evitar a perda de progresso durante o desenvolvimento."**

### Critérios de validação:

- Cada etapa do tratamento dos dados deve estar organizada e documentada no Google Colab.
- Os arquivos gerados durante as etapas de limpeza e transformação devem ser armazenados no GitHub.
- O histórico de alterações deve estar disponível por meio do versionamento do repositório.
- A equipe deve conseguir identificar e recuperar versões anteriores dos dados quando necessário.

---

# 📌 Definition of Ready (DoR) – Sprint 3

Antes do início da Sprint 3, todas as User Stories selecionadas devem atender aos critérios abaixo, garantindo que estejam prontas para desenvolvimento.

## Sobre as User Stories:

- Possuem título claro, descrição bem definida e objetivo compreendido.
- Estão escritas no formato padrão: **"Como cliente, quero..., para..."**.
- Possuem critérios de validação definidos.
- Possuem regras de negócio claras e documentadas.
- Estão alinhadas ao escopo do projeto de análise de importação e exportação dos municípios do estado de São Paulo.
- Não possuem dependências bloqueadoras para desenvolvimento.
- Foram compreendidas e validadas pelo time.

## Sobre os artefatos correlatos às User Stories:

- Dashboards das Sprints 1 e 2 disponíveis para evolução.
- Dados de importação e exportação tratados e organizados.
- Fonte de dados (ComexStat) definida e acessível.
- Estrutura de versionamento configurada no GitHub.
- Scripts de tratamento de dados disponíveis no Google Colab.
- Regras de cálculo do Saldo Comercial documentadas.
- Estratégia de testes definida para validação dos indicadores e filtros.

---

# 📌 Definition of Done (DoD) – Sprint 3

A Sprint 3 só pode ser considerada concluída quando atender aos seguintes critérios:

- Comparação do saldo comercial entre municípios implementada e funcionando corretamente.
- Indicadores de exportação, importação e saldo comercial calculados e validados.
- Filtros por município, país, mês e ano funcionando corretamente.
- Documentação das fontes de dados e fórmulas de cálculo concluída.
- Arquivos e scripts versionados no GitHub.
- Dashboards atualizados com as análises de superávit e déficit comercial.
- Testes realizados pelos membros da equipe para validação dos dados e dashboards.
- Backlog da Sprint 3 documentado.
- Repositório GitHub atualizado com os artefatos produzidos na Sprint.
- Atividades da Sprint documentadas no relatório parcial do projeto.
- Todos os critérios de validação das User Stories atendidos e aprovados pela equipe.
