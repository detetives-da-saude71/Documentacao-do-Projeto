# Análise SWOT e Planejamento Estratégico (TOWS) — Detetives da Saúde

## 1. Contexto e Governança
Este documento apresenta o diagnóstico situacional e o alinhamento estratégico do projeto **Detetives da Saúde** para a condução da Sprint Final. O objetivo principal é garantir a entrega de uma plataforma web educativa de alta qualidade para o ensino de prevenção de doenças infecciosas.

---

## 2. Matriz SWOT (Diagnóstico Situacional)

| Fatores Internos | Fatores Externos |
| :--- | :--- |
| **Forças (Strengths)**<br>- Domínio técnico da equipe no stack (Node.js, Express, Sequelize e JavaScript).<br>- Organização clara do repositório e uso de metodologias ágeis (GitHub Projects).<br>- Arquitetura REST flexível e modular. | **Oportunidades (Opportunities)**<br>- Alta demanda por ferramentas educativas gamificadas no ensino fundamental.<br>- Boa aceitação de soluções de apoio pedagógico sobre saúde pública nas escolas.<br>- Possibilidade de expansão do catálogo de jogos/quizzes. |
| **Fraquezas (Weaknesses)**<br>- Tempo restrito para implementação de mecânicas complexas de jogo.<br>- Infraestrutura física local limitada para testes de carga em alta escala.<br>- Curva de ajuste para estilização visual e responsividade em múltiplos dispositivos. | **Ameaças (Threats)**<br>- Prazo final curto de entrega do projeto (Sprint Final).<br>- Oscilações em conexões de rede durante a validação de serviços cloud.<br>- Risco de escopo inflado (escopo aberto) comprometer a entrega principal. |

---

## 3. Matriz de Confronto (TOWS) e Estratégias

### Estratégias FO (Forças + Oportunidades)
- **Aproveitamento Tecnológico:** Utilizar o conhecimento consolidado no ecossistema Node.js/Sequelize para acelerar a entrega do módulo principal de quizzes e rankings educativos.

### Estratégias FA (Forças + Ameaças)
- **Blindagem de Escopo:** Utilizar a organização rigorosa do GitHub Projects para priorizar apenas funcionalidades vitais, mitigando o risco do prazo curto.

### Estratégias DO (Fraquezas + Oportunidades)
- **Foco na Usabilidade Essencial:** Simplificar a interface e as mecânicas de jogo para garantir que o produto seja intuitivo para o público infantil, contornando limitações de tempo de desenvolvimento.

### Estratégias DA (Fraquezas + Ameaças) — Plano de Contingência
- **Congelamento de Features (Feature Freeze):** Caso haja atraso nos testes, congelar novas funcionalidades e focar exclusivamente na correção de bugs críticos e estabilidade do fluxo principal.

---

## 4. Repriorização do Backlog (Método MoSCoW)

* **Must Have (Obrigatório):**
  - Autenticação e cadastro de usuários/alunos.
  - Módulo principal do jogo/quiz sobre prevenção de doenças infecciosas.
  - Persistência da pontuação e progresso do aluno no banco de dados.
* **Should Have (Desejável/Importante):**
  - Dashboard visual com estatísticas de desempenho para o professor.
  - Animações e efeitos sonoros de feedback de resposta.
* **Could Have (Opcional):**
  - Personalização de avatares dos alunos.
  - Modo escuro (Dark Mode) no portal de gestão.
* **Won't Have (Fora desta Sprint):**
  - Multiplayer online em tempo real.
  - Aplicativo nativo mobile (iOS/Android).

---
