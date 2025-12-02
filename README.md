# 💸 App FinanceAI para Controle de Finanças Pessoais com Vibe Coding

### O que é Vibe Coding?

- É uma forma de programar focada na experiência e no fluxo criativo, usada no Lovable.  
- Em vez de começar com código técnico pesado, exploramos ideias de forma leve e iterativa.  

**Características:**
- **Experimentação rápida:** testar hipóteses sem medo de errar.  
- **Feedback imediato:** ver resultados e ajustar na hora.  
- **Foco na experiência do usuário:** pensar mais em como o app “se sente” do que em detalhes técnicos.  


## 🎯 Desafio

Estruturar um plano de MVP (Produto Mínimo Viável) para um aplicativo de Organização de Finanças Pessoais com foco em simplicidade, conversa natural e recomendações inteligentes, e criar um PRD para incluir a funcionalidade de visualização gráfica das despesas e receitas, garantindo que os relatórios sejam ainda mais claros e acessíveis.

## 🪄 Etapas do Desafio

### 1. MVP

Objetivo do MVP: Validar se os usuários iniciantes conseguem organizar suas finanças de forma prática e sem complicação, usando apenas interações em linguagem natural, sem formulários complexos.

Principais Telas do MVP

- **Tela de Boas-Vindas / Onboarding**
  - Explica rapidamente como funciona o app (registrar gastos via conversa).
  - Pergunta objetivos iniciais: “Você quer controlar gastos, economizar ou definir uma meta?”

- **Tela de Conversa (Chat Financeiro)**
  - Interface semelhante a um mensageiro.
  - Usuário digita frases como: “Gastei 50 reais no supermercado”.
  - O app interpreta, classifica e registra automaticamente.

- **Tela de Metas**
  - Usuário define metas simples: “Quero economizar 200 reais este mês”.
  - Mostra progresso com barra ou indicador visual.

- **Tela de Relatórios Simples**
  - Gráficos básicos (pizza ou barras) mostrando categorias de gastos.
  - Resumo semanal/mensal em linguagem acessível: “Você gastou mais em alimentação este mês”.

- **Tela de Dicas do Agente Financeiro**
  - Recomendações automáticas baseadas nos hábitos do usuário.


**Exemplo:**  
“Você gastou muito em delivery. Que tal cozinhar em casa 2 vezes por semana?”

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê.  
Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.


### 2. PRD

PRD = documento que organiza e comunica os requisitos do produto.

Usamos o modelo PRD como ponto de partida e adaptamos conforme o nosso estilo:

```txt
PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

1. Visão Geral
Um aplicativo que permite ao usuário organizar suas finanças pessoais por meio de conversas em linguagem natural. 
O objetivo é simplificar o controle financeiro, evitando formulários complexos e planilhas, e oferecendo recomendações automáticas de economia.  
Princípio central: o app deve adotar Design Universal, garantindo que pessoas com diferentes perfis, idades, níveis de letramento digital e possíveis limitações possam usar a solução com boa experiência.

2. Problema
- Usuários iniciantes desistem de controlar gastos porque os apps atuais exigem muita entrada manual.  
- Falta personalização e experiência amigável.  
- Pouca orientação prática para manter hábitos de economia.  
- Relatórios pouco visuais dificultam a compreensão rápida dos gastos.

3. Objetivo do Produto
Facilitar o controle financeiro de forma prática e natural, ajudando iniciantes a:  
- Registrar gastos sem esforço.  
- Entender seus hábitos de consumo.  
- Receber dicas personalizadas para economizar.  
- Acompanhar metas simples e realistas.  
- Visualizar despesas e receitas em gráficos claros e atualizados automaticamente.  
- Garantir acessibilidade e usabilidade ampla (design universal).

4. Público-Alvo
- Pessoas que querem começar a organizar suas finanças sem complicação.  
- Usuários leigos em finanças e tecnologia.  
- Jovens adultos e trabalhadores que buscam praticidade.  
- Pessoas com diferentes níveis de alfabetização digital e necessidades de acessibilidade.

5. Funcionalidades-Chave (MVP)
1. Registro de gastos via chat em linguagem natural.  
2. Classificação automática das transações (alimentação, transporte, lazer etc.).  
3. Definição de metas financeiras simples (ex.: economizar R$200/mês).  
4. Agente Financeiro que envia dicas de economia personalizadas.  
5. Relatórios visuais e textuais claros e acessíveis.  
6. Visualização Gráfica das Despesas e Receitas:  
   - Gráfico de Barras: mostra evolução dos gastos por categoria ao longo do tempo.  
   - Gráfico de Pizza: mostra proporção dos gastos por categoria.  
   - Legendas claras e acessíveis para cada categoria.  
   - Atualização automática conforme novas despesas ou receitas são registradas.  
7. Design Universal: interface simples, textos claros, contraste adequado, suporte a leitores de tela e navegação intuitiva.

6. Fluxo do Usuário
Onboarding → Chat Financeiro → Registro automático → Relatórios → Gráficos (barras/pizza) → Metas → Recomendações.

7. Critérios de Sucesso
- Usuários conseguem registrar gastos sem dificuldade.  
- Pelo menos 70% entendem os relatórios e gráficos sem precisar de explicações adicionais.  
- Usuários relatam que as dicas são úteis e aplicáveis.  
- O app é avaliado como inclusivo e acessível por diferentes perfis de usuários.  
- Gráficos são considerados claros e ajudam na tomada de decisão financeira.

8. Validação Inicial
- Teste com 5–10 usuários reais, incluindo diversidade de idade e nível de experiência digital.  
- Métricas: número de registros semanais, metas criadas, feedback sobre clareza das dicas e gráficos.  
- Iteração rápida para ajustar categorias, linguagem e acessibilidade dos relatórios visuais.

```

Usamos o Copilot Web para revisar e melhorar o prompt antes de ir ao Lovable. 

### 3. Explorando o Lovable na Prática

Com o PRD pronto e revisado, incluimos o prompt e fizemos as seguintes interações com o Lovable: 

1. O app deve tornar possível a criação de metas e registro delas nele, através da conversa com o agente, uma tela com visualização simples e completa dos extratos no formato bancário além dos gráficos visuais(pizza e barra) em outra tela para acompanhamento em tempo real. Além da categorização das receitas e despesas de forma intuitiva e atraente. Se possível dê uma cara personalizada com possível inclusão de foto e chamando o usuário pelo nome. Além disso, que seja possível fazer upload do extrato bancário e/ou da fatura do cartão no formato pdf para controle total financeiro do usuário.

2. Corrija as seguintes inconsistencias: 1) ao tentar importar as transações através do upload da fatura de cartão e do extrato da conta em pdf, o app retorna a seguinte mensagem ou erro "Funcionalidade de parsing de PDF será implementada em breve!" e não funciona. 2) Ao tentar solicitar ao agente para apagar, excluir ou substituir alguma despesa ou receita cadastrada, o app retorna a seguinte mensagem  "Olá, entendo que você queira excluir a transação no valor de x reais cadastrada em tal categoria, mas meus recursos atuais não me permitem remover transações já cadastradas." 3) Gostaria ainda que os graficos fossem exibidos na primeira tela, que seja atualiza em tempo real conforme as entradas e saídas cadastradas, não em outra aba. 4) Gostaria ainda que as entradas e saídas também possam ser cadastradas clicando nas opções correspondentes "Receitas" e "Despesas" não apenas através do Agente, mas que ele informe aquela entrada ou saída,  sugerindo ou orientando ao usuário de forma pro-ativa sobre dicas financeiras ou funcionalidades do app.
3. Altere as cores do tema do app de verde para mais azulado.
4. Inclua as seguintes despesas academia, internet, agua, luz, supermercado, restaurante,  salão, vestuário, itens de beleza, passagens, transporte e permita cadastrar uma despesa ou receita personalizada.

### 4.CONCLUSÃO

Resultado Final > É possível acessar o app através do link : https://financasbyflaviofox.lovable.app/dashboard


<img width="942" height="823" alt="image" src="https://github.com/user-attachments/assets/2ec516b1-bc62-4847-bbbe-ca832a042e09" />


# Resumo das Funcionalidades do App

## Registro de Gastos via Conversa
- Usuário informa despesas em linguagem natural (ex.: “Gastei 50 reais no supermercado”).  
- O app interpreta, classifica e registra automaticamente.

## Classificação Automática
- Transações categorizadas em alimentação, transporte, lazer, etc.  
- Organização intuitiva e atraente para facilitar a compreensão.

## Metas Financeiras
- Criação e acompanhamento de metas simples (ex.: economizar R$200/mês).  
- Progresso mostrado em barras ou indicadores visuais.  
- Registro de metas feito diretamente na conversa com o agente.

## Relatórios Simples e Personalizados
- Resumo semanal/mensal em linguagem acessível.  
- Destaque de hábitos de consumo (ex.: “Você gastou mais em alimentação este mês”).

## Visualização Gráfica
- **Gráfico de Barras:** evolução dos gastos por categoria ao longo do tempo.  
- **Gráfico de Pizza:** proporção dos gastos por categoria.  
- Legendas claras e acessíveis.  
- Atualização automática conforme novas despesas ou receitas são registradas.

## Agente Financeiro
- Recomendações automáticas de economia baseadas nos hábitos do usuário.  
- Sugestões práticas e personalizadas (ex.: “Você gastou muito em delivery, que tal cozinhar em casa?”).

## Upload de Documentos
- Possibilidade de enviar extratos bancários e faturas de cartão em PDF.  
- Integração dos dados para controle financeiro completo.

## Visualização de Extratos
- Tela com extratos no formato bancário, simples e completo.  
- Permite acompanhar receitas e despesas em tempo real.

## Personalização da Experiência
- Inclusão de foto do usuário no perfil.  
- Chamadas personalizadas pelo nome para maior proximidade.

## Design Universal
- Interface simples e inclusiva.  
- Textos claros, contraste adequado, suporte a leitores de tela e navegação intuitiva.  
- Experiência pensada para o maior número possível de usuários, independentemente de idade ou nível de letramento

### 5. REFLEXÃO
A utilização da Inteligência Artificial amplia ainda mais os benefícios, pois permite implementar aplicativos completos com pouco conhecimento de código, aproveitando plataformas que automatizam grande parte do desenvolvimento. Além disso, a IA embarcada no app atua como um agente financeiro inteligente, capaz de interagir diretamente com o usuário, oferecer recomendações personalizadas e adaptar-se ao comportamento individual, tornando a experiência mais prática, inclusiva e envolvente.

Outro ponto essencial é transformar dados financeiros em informações visuais e personalizadas. Gráficos de pizza e barras tornam os padrões de consumo mais fáceis de compreender, enquanto o agente financeiro cria proximidade ao oferecer dicas práticas e chamar o usuário pelo nome.

O plano gratuito do Lovable com interações limitadas por dia não permitiu resolver alguns erros no app, principalmente na funcionalidade de upload de documentos em formato PDF para automatizar o registro das despesas e receitas, mas que também despertou um alerta deste procedimento de risco já que são faturas e extratos bancários são dados sensíveis e pessoais. Em outro momento poderemos estudar uma melhor forma de fazer isso. 

 O verdadeiro objetivo do desafio foi alcançado, aprender a criar um aplicativo funcional com IA, equilibrando simplicidade, acessibilidade e inteligência, validando que o app realmente ajuda iniciantes a manter o hábito de controlar suas finanças.


