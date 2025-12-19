# Edufinanciar 📘💰
**Protótipo de Alfabetização Financeira Digital e Simulação de Interface**

Este projeto é um Produto Mínimo Viável (MVP) desenvolvido como Trabalho de Conclusão de Curso (TCC) em Sistemas de Informação. O foco principal é auxiliar usuários leigos e idosos na transição para o sistema bancário digital através de educação teórica e prática simulada.

---

## 🚀 Funcionalidades Principais

### 1. Módulos de Aprendizagem (6 Módulos)
- Estrutura educativa dividida em: Bancos e Contas, Cartões, Apps de Pagamento, Segurança Digital, Orçamento e Investimentos.
- Conteúdo focado em usabilidade e prevenção de golpes (Phishing).

### 2. Avaliação e Gamificação (60 Questões)
- **Banco de Questões:** Cada um dos 6 módulos possui 10 perguntas específicas.
- **Simulado Geral:** Uma aba dedicada com 60 questões consolidadas para testar o conhecimento total.
- **Sistema de XP:** Cada acerto gera 10 pontos de XP, salvos localmente via `AsyncStorage`.
- **Streak (Ofensiva):** Contador de dias consecutivos para incentivar a retenção do aprendizado.

### 3. Simulação de Interface Bancária
- Ambiente de treino livre ("Sandbox") com contas simuladas.
- Fluxos de visualização de saldo, extrato e simulação de envio de Pix.
- **Nota Técnica:** Este módulo não gera pontuação e utiliza dados fictícios (Mock Data) para garantir um ambiente de aprendizado sem riscos financeiros.

---

## 🛠️ Tecnologias e Arquitetura

- **Framework:** React Native (Expo).
- **Persistência de Dados:** `AsyncStorage` (Persistência local do progresso do usuário).
- **Gerenciamento de Estado:** React Context API para simulação do banco.
- **Navegação:** React Navigation (Stack e Tab Navigators).

---

## 📊 Metodologia e Validação
O desenvolvimento foi orientado por uma pesquisa de campo com **30 participantes reais**. Os requisitos de software e o banco de 60 questões foram elaborados para sanar as dores identificadas nesta amostra (dificuldade com tecnologia e medo de fraudes).

---

## ⚠️ Observações de Desempenho
O protótipo foi otimizado para visualização em ambiente de desenvolvimento. Devido à densidade do banco de questões e à complexidade dos navegadores em um arquivo único (arquitetura monolítica para o Expo Snack), podem ocorrer limitações de renderização em dispositivos físicos limitados. A lógica de negócio e persistência, entretanto, está integralmente funcional no código-fonte.

---
Desenvolvido por Alexandre Vieira Leonardo - TCC Sistemas de Informação.
