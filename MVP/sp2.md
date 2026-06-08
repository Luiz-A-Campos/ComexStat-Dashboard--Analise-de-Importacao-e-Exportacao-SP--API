# 📌 MVP - Aldo Pereira Solutions.

## 🎯 Objetivo do MVP
O MVP (Produto Mínimo Viável) da Sprint 2 tem como objetivo ampliar e aprimorar a plataforma de BI desenvolvida na Sprint 1, expandindo as análises de comércio exterior dos municípios do estado de São Paulo por meio de dashboards mais completos e interativos.

- **Problema a ser resolvido:** 
Os dados de comércio exterior encontram-se distribuídos em grandes bases de dados, dificultando a análise integrada de importações e exportações, a identificação de tendências econômicas e a compreensão dos indicadores logísticos dos municípios paulistas.

- **Hipótese a ser validada:** Se os dashboards forem ampliados com novos indicadores, filtros por municípios e dados atualizados de importação e exportação, será possível realizar análises mais detalhadas e eficientes, facilitando a interpretação dos dados e apoiando a tomada de decisão.

- **Valor entregue:** O MVP entrega dashboards interativos contendo informações de importação e exportação dos municípios do estado de São Paulo entre 2021 e 2026, permitindo visualizar produtos comercializados, países envolvidos nas operações, valores financeiros, modais de transporte, movimentações logísticas e indicadores estatísticos de forma organizada e acessível.

---

## 📝 Descrição da Solução
Nesta sprint, será realizada a continuidade do projeto iniciado anteriormente, com melhorias estruturais e visuais nos dashboards existentes, além da ampliação da base de dados utilizada nas análises.

Os dashboards passam a incluir informações de 2021 a 2026, incorporando filtros por municípios, produtos SH4, países exportados, anos, meses, modais de transporte, etc.

**Funcionalidades principais incluídas:**

### Dashboard de Exportação

- Mapa de localização do Estado de São Paulo;
- Soma do Valor FOB em dólar;
- Total de produtos exportados;
- Mapa de visualização dos países exportados;
- Gráfico de participação dos produtos em porcentagem;
- Tabela de vias e seus totais de movimentações.

#### Filtros

- Municípios;
- Produtos em SH4;
- Países exportados;
- Ano (2021 a 2026);
- Mês.

### Dashboard de Importação

- Soma do valor em dólar;
- Quantidade estatística;
- Peso total líquido dos produtos (KG);
- Número total de operações;
- Mapa de localização do Estado de São Paulo;
- Soma do valor de frete;
- Ranking das vias por Valor FOB;
- Evolução do Valor FOB por ano.

#### Filtros

- Ano;
- Mês;
- Municípios;
- País;
- Modais de transporte (via);
- Produtos.


**Limitações conhecidas:**

- Plataforma ainda limitada ao Power BI;
- Dependência de tratamento manual dos dados;
- Ausência de análises preditivas e projeções futuras;
- Algumas análises avançadas ainda não foram adicionadas.

**Escopo reduzido:**

- Expansão dos dashboards de exportação para o período de 2021 a 2026;
- Desenvolvimento dos dashboards de importação;
- Implementação de filtros por municípios, produtos, países e períodos;
- Inclusão de indicadores logísticos e econômicos;
- Melhoria visual e estrutural das análises.

---

## 👥 Personas / Usuários-Alvo

## 👥 Persona 1: Analista Institucional de Dados (CADI)
Profissional responsável por acompanhar o desempenho econômico e comercial dos municípios do estado de São Paulo.

- **Necessidades:**
Necessita analisar grandes volumes de dados de comércio exterior para identificar padrões, tendências e comparações regionais. Entretanto, enfrenta dificuldades devido à falta de organização e padronização das informações.

- **Dores atendidas:**
O MVP disponibiliza dashboards organizados e filtros por municípios, permitindo análises mais rápidas, comparações eficientes e melhor interpretação dos indicadores econômicos.
    
## 👥 Persona 2: Estudante/Pesquisador
Usuário acadêmico que realiza pesquisas relacionadas à logística, economia e comércio exterior.

- **Necessidades:**
Precisa acessar dados estruturados e confiáveis para desenvolvimento de estudos e análises exploratórias, reduzindo o tempo gasto com coleta e tratamento manual das informações.

- **Dores atendidas:**
O MVP oferece uma base de dados organizada e dashboards interativos, facilitando análises acadêmicas e interpretação de padrões comerciais.

## 👥 Persona 3: Analista de Logística
Profissional responsável pelo planejamento e análise das operações logísticas e comerciais.

- **Necessidades:** Busca compreender custos logísticos, países envolvidos nas operações comerciais e produtos movimentados, porém enfrenta dificuldades devido à falta de visualização integrada dessas informações.

- **Dores atendidas:** O MVP disponibiliza dashboards específicos de importação contendo indicadores logísticos, custos de transporte, produtos importados e quantidade estatística, facilitando análises operacionais.
 

---

## 🔑 User Stories (Backlog do MVP)
| Rank | Prioridade | User Story (Sprint 2) | Sprint |
|------|------------|----------------------|--------|
| 1  | Alta  | Como cliente, quero visualizar a evolução histórica das importações de SJC por categoria de produto, para monitorar a dependência de insumos externos e o crescimento industrial local. | 2 |
| 2  | Média | Como cliente, quero identificar os modais de transporte predominantes no estado de SP para priorizar investimentos em infraestrutura e manutenção dessas vias. | 2 |
| 3 | Baixa | Como cliente, quero visualizar um ranking dos modais de transporte menos utilizados nas exportações para identificar oportunidades de diversificação logística ou gargalos em modais subutilizados. | 2 |
| 4 | Baixa | Como cliente, quero filtrar os principais países parceiros comerciais do estado de SP para entender a influência geopolítica e econômica de mercados estrangeiros na economia paulista. | 2 |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Tabelas de exportação, Desenvolvimento inicial do dashboard no Power BI, Filtro de dados para São Paulo.                        | Concluído|
| 02     | Expansão dos dashboards, dashboards de importação, filtros por municípios e melhorias organizacionais.                           | Concluído |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize e analise dados de importação e exportação por municípios do estado de São Paulo utilizando dashboards interativos e filtros dinâmicos.
- O sistema deve registrar os dados de comércio exterior organizados em tabelas estruturadas, garantindo clareza e consistência das informações apresentadas.
- Métricas coletadas:
  - Tempo de resposta dos dashboards;
  - Taxa de utilização dos filtros;
  - Tempo médio de navegação;
  - Número de análises realizadas;
  - Desempenho no carregamento das visualizações.


---

## 📈 Métricas de Validação
## **Número de usuários que testaram o MVP:**

Os testes foram realizados por membros da equipe, sendo:

* Luiz Augusto (Scrum Master - SM);
* Rita Carolina (Team Member - TM).
 
## **Feedback qualitativo (positivo/negativo):**

Os feedbacks foram positivos em relação à organização dos dashboards, clareza das informações e melhoria dos filtros. Também foram destacadas oportunidades de melhoria relacionadas aos tipos de filtros que poderiam ser incluídos.
    
## **Indicadores de negócio:**
- Redução do tempo de análise de dados;
- Aumento da eficiência na tomada de decisão;
- Melhoria na visualização e interpretação das informações;
- Apoio na identificação de oportunidades no comércio exterior;
- Redução de custos operacionais com análise manual de dados;
- Otimização dos custos logísticos.

---

## 5W2H

| What (O quê) | Why (Por quê) | Where (Onde) | When (Quando) | Who (Quem) | How (Como) | How Much (Quanto/tempo) |
|-------------|---------------|--------------|---------------|------------|------------|-------------------|
| Revisão final dos códigos | Garantir que todas as funcionalidades estejam funcionando corretamente | Python / Power BI | Durante a Sprint | Felipe Borges | Revisão do código, correção de erros, otimização e validação final das funcionalidades | 4 semanas |
| Finalização do dashboard | Garantir visualização clara, interativa e pronta para apresentação | Power BI | Durante a Sprint | José Augusto, Tiago Rafael e Rita Carolina | Ajustes finais nos gráficos, padronização visual e testes de interação | 4 semanas |
| Análise final dos dados | Consolidar insights e gerar conclusões estratégicas | Power BI / Reuniões | Durante a Sprint | Luiz Augusto e Luiz Gustavo | Revisão das análises, validação dos resultados e definição dos principais insights | 4 semanas |
| Organização do repositório | Garantir controle de versões e organização dos arquivos finais | GitHub | Final da Sprint | Yuri Ribeiro | Atualização dos arquivos, versionamento final e organização do repositório | 4 semanas |
| Criação do roteiro da apresentação | Garantir clareza, organização e fluidez no vídeo | Documento compartilhado | Início da Sprint | Aldo Pereira, Ana Carolina e Rita Carolina | Estruturação da narrativa, divisão de falas e organização dos conteúdos | 4 semanas |
| Levantamento de dúvidas e alinhamento do backlog | Garantir que não haja pendências no projeto | Reuniões da equipe | Durante a Sprint | Ana Carolina | Organização dos questionamentos, acompanhamento das pendências e validação das entregas | 4 semanas |
| Relatório final | Documentar todo o projeto e seus resultados | Word | Durante o Projeto | José Augusto | Escrita estruturada, revisão e formatação conforme normas | 4 semanas |

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências

### - Prints de tela:

#### **Importação:**

<img width="1290" height="736" alt="WhatsApp Image 2026-05-22 at 15 49 56 (1)" src="https://github.com/user-attachments/assets/b5f211ef-aa28-416b-bc33-cd44596525e4" />

<img width="1852" height="851" alt="Captura de tela 2026-05-25 162646" src="https://github.com/user-attachments/assets/4671a42d-d3e4-4990-90ea-b3342d7384a5" />

<img width="1777" height="726" alt="Captura de tela 2026-05-25 162743" src="https://github.com/user-attachments/assets/b34b07d6-cd46-47b2-8671-890a4837c490" />

<img width="1762" height="72" alt="Captura de tela 2026-05-25 162834" src="https://github.com/user-attachments/assets/a33da5c5-92ef-4221-87cb-6e195e0fe093" />

---

<img width="1855" height="857" alt="1" src="https://github.com/user-attachments/assets/b9c99597-3fa6-4ab4-87b8-0efd0d5c8fd5" />

<img width="1868" height="742" alt="2" src="https://github.com/user-attachments/assets/9b07d7c3-53a0-442e-967e-9b34f37a004c" />

<img width="1871" height="728" alt="3" src="https://github.com/user-attachments/assets/3cf3b761-a56d-4655-bacd-6140fdd25e94" />

<img width="1870" height="741" alt="4" src="https://github.com/user-attachments/assets/a102e95d-bd3b-4d18-ae38-63bd91d372d8" />

<img width="1862" height="620" alt="5" src="https://github.com/user-attachments/assets/3fd76b4e-6e6e-4bf8-baad-97f15094ca84" />

---

### **Exportação:**

<img width="1290" height="736" alt="WhatsApp Image 2026-05-22 at 15 49 56 (1)" src="https://github.com/user-attachments/assets/c26b8021-6b16-42e7-a8ed-b4a1f9fe3b30" />

<img width="1867" height="848" alt="a" src="https://github.com/user-attachments/assets/cf2deddc-d2ef-4267-a19f-7d690576288f" />

<img width="1870" height="733" alt="b" src="https://github.com/user-attachments/assets/905ab46d-812b-4dae-a0b7-49ae7d46de97" />

<img width="1872" height="730" alt="c " src="https://github.com/user-attachments/assets/ceb8dd05-9aee-456b-98b0-76ad05f30753" />

<img width="1868" height="430" alt="d" src="https://github.com/user-attachments/assets/deee9ce5-d3a9-42e0-a485-7aee00ed5188" />

---

<img width="1871" height="841" alt="aa" src="https://github.com/user-attachments/assets/40501bc1-1da4-472a-80bd-e260bbc4c6a4" />

<img width="1870" height="733" alt="bb" src="https://github.com/user-attachments/assets/090117e7-e400-4041-8aeb-4dedc3026c85" />

<img width="1870" height="732" alt="cc" src="https://github.com/user-attachments/assets/51405efa-1961-48d9-80a1-958b17556fd3" />

<img width="1873" height="722" alt="dd" src="https://github.com/user-attachments/assets/330ae1eb-c1be-464a-a133-6427a47bae27" />

<img width="1867" height="516" alt="ee" src="https://github.com/user-attachments/assets/ae9f7632-ff10-4113-ab5d-083dc83511f1" />

---

- Fluxos ou protótipos: https://drive.google.com/drive/folders/1cyFB0D47e_sD2grL4PLvKERHOpEPR9hu?usp=drive_link

---

- Vídeo (MVP): https://youtu.be/gOLNpZY3Jg8
