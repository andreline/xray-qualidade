# 📘 X-Ray na Prática: Guia Estratégico para QA

Este repositório é um compilado completo sobre o uso da ferramenta **X-Ray integrada ao Jira** para gestão de qualidade de software. Aqui você vai encontrar desde o que é o X-Ray, até como aplicá-lo na prática para documentar testes, estruturar execuções regressivas, organizar bug bashes e obter métricas rastreáveis para o seu time.

---

## 🧠 O que é o X-Ray?

O X-Ray é uma extensão poderosa do Jira que permite documentar, planejar e executar casos de teste. Com ele, você:

- Centraliza toda a documentação de testes em um só lugar
- Organiza testes por produto, app, sprint ou funcionalidades
- Executa testes manuais e automatizados
- Cria rastreabilidade entre requisitos, cenários e defeitos
- Gera métricas visuais e relatórios automatizados

💡 É ideal para equipes que querem formalizar seus testes, escalar a cobertura e ter rastreabilidade sem sair do Jira.

---

## ✍️ X-Ray Guideline — Boas Práticas

A guideline é a base estratégica para garantir que o uso do X-Ray seja consistente e eficiente. Ela orienta como estruturar testes desde o início do ciclo de desenvolvimento. Veja os pontos-chave:

### ✅ Vantagens:
- Organização centralizada da documentação
- Rastreabilidade entre requisitos e testes
- Facilidade em criar métricas e relatórios
- Redução de retrabalho entre squads
- Suporte a testes exploratórios e regressivos

### ⚠️ Desafios:
- Requer esforço inicial do time para mapear os fluxos
- Exige manutenção contínua da documentação

### 🧭 Quando aplicar:
- Desde a fase de planejamento da sprint, vinculado aos requisitos
- Durante o desenvolvimento (unitários e integração)
- Nas execuções regressivas
- Em ciclos de melhoria contínua, como parte do processo de QA

---

## 🚀 Como usar o X-Ray na prática

### 🛠️ Estrutura de Itens no Jira:
- **Xray Test** → Para documentar fluxos e casos de testes (em BDD ou passo a passo)
- **Test Set / Test Plan** → Para agrupar testes por app, sprint, versão, produto ou release
- **Test Execution** → Para rodar os testes, registrar bugs e gerar evidência e métricas

### 🗂️ Criando um Projeto para o X-Ray
1. Crie um projeto no Jira com a estrutura Scrum ou Kanban
2. Vá em **Configurações do Projeto > Tipos de Itens**
3. Adicione os tipos: `Xray Test`, `Test Plan`, `Test Set`, `Test Execution`

### 🧪 Criando Documentações com Xray Test
- Crie uma tarefa do tipo **Xray Test**
- Use títulos com formato: `[Etapa] Fluxo - App`
- Preencha descrição com pré-condições necessárias
- Crie os Steps: Ação, Dado e Resultado Esperado
- Adicione evidências (fotos, gifs, vídeos) nos Steps

### 📚 Organizando por Test Plan / Test Set
- Crie um Test Plan para agrupar os testes de uma versão, produto, sprint, etc.
- Use o botão **Add Tests** para adicionar os Xray Test que compõem o grupo
- Isso facilita executar regressivos com apenas 1 clique

### ▶️ Rodando os Testes com Test Execution
- Crie uma tarefa de Test Execution vinculada a um Test Plan ou do zero
- Execute os testes com botões (✅ passou / ⚠️ em execução / ❌ falhou)
- Adicione comentários, bugs e evidências em cada Step
- Gere relatórios automaticamente ao final

---

## 🔁 Como aplicar no dia a dia

- Organize seus testes por app, fluxo e tipo de validação
- Use Test Plans para cada ciclo (sprint, release, hotfix)
- Crie bibliotecas com Test Sets reutilizáveis por produto
- Execute regressivos com base em Test Executions de forma rápida e rastreável
- Gere relatórios com o **Xray Document Generator** para evidenciar os testes executados

---

## 💡 Dicas Estratégicas

- Nomeie as tarefas sempre com clareza (etapa + fluxo + app)
- Mantenha as descrições bem preenchidas com contexto e pré-condições
- Priorize cobertura: revise os testes periodicamente para incluir novos fluxos
- Use evidência sempre: print, gif, vídeo — tudo ajuda na rastreabilidade

---

## 🌍 Links úteis

- 🌐 [Site oficial do X-Ray](https://www.getxray.app/)
- 📄 [Documentação oficial](https://docs.getxray.app/)
- 💰 [Tabela de preços](https://marketplace.atlassian.com/apps/1211769/xray-test-management-for-jira?tab=pricing&hosting=cloud)

---

Feito com 💜 por [Andreline Lira](https://www.linkedin.com/in/andrelineflira)

> Este conteúdo é baseado em experiências reais de QA e tem como objetivo ajudar outras pessoas a aplicarem o X-Ray de forma eficiente e estratégica no seu time.
