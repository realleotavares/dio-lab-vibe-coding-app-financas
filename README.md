# Financas Facil - Vibe Coding

## Sobre o Projeto
Este projeto e a entrega do desafio "Criando um App de Financas Pessoais com IA" da DIO. O objetivo foi aplicar o conceito de Vibe Coding, utilizando o Microsoft Copilot para refinar um Product Requirement Document (PRD) e o Lovable para gerar um prototipo funcional de um aplicativo de financas baseado em conversas em linguagem natural.

---

## PRD Refinado no Copilot Web

### Contexto
Desenvolver um aplicativo de organizacao de financas pessoais baseado em conversas em linguagem natural. O objetivo e simplificar o controle financeiro, eliminando a necessidade de formularios complexos ou planilhas, e oferecendo uma experiencia mais humana e acessivel.

### Problema
Usuarios frequentemente abandonam aplicativos de financas porque exigem entradas manuais extensas e oferecem pouca personalizacao. A proposta e resolver isso com uma interface conversacional e recomendacoes automaticas de economia.

### Publico-alvo
Individuos que desejam iniciar o controle de suas financas de forma pratica e descomplicada, especialmente iniciantes sem experiencia previa em gestao financeira.

### Funcionalidades-chave (MVP)
- Registro via chat: Inserir gastos e receitas por meio de conversas em linguagem natural.  
- Classificacao automatica: Categorizar transacoes sem esforco manual.  
- Metas financeiras: Criar e acompanhar objetivos como poupar ou quitar dividas.  
- Dicas de economia: Receber sugestoes praticas de um agente financeiro virtual.  
- Relatorios personalizados: Visualizar graficos e resumos simples adaptados ao perfil do usuario.  

### Design Universal
O aplicativo deve ser projetado com principios de design universal, garantindo acessibilidade e usabilidade para o maior numero possivel de pessoas, independentemente de idade, experiencia tecnologica ou possiveis limitacoes fisicas/cognitivas. Isso inclui:
- Interface clara e intuitiva.  
- Compatibilidade com leitores de tela.  
- Uso de contrastes adequados e fontes legiveis.  
- Navegacao simplificada e consistente.  

### Entregavel esperado da IA
- Plano de MVP com telas principais (chat, dashboard, metas, relatorios).  
- Esboco de validacao inicial (testes com usuarios iniciantes para medir clareza e engajamento).  

### Tom
Educativo, acessivel e em portugues simples, para facilitar a compreensao de usuarios iniciantes.

---

## Interacoes com o Lovable

**Interacao 1 (Unica e Certeira):**
> Cria um app de financas pessoais com base no seguinte PRD: [Inclusao do PRD completo detalhado acima].

Nota: O prompt foi tao bem estruturado no Copilot que o Lovable precisou de apenas uma interacao principal para gerar o app funcional, fazendo apenas perguntas de clarificacao sobre o uso de banco de dados e layout.

---

## Resultado Final no Lovable

**Link de acesso:** https://financafacil-ria.lovable.app

### Telas do App:
(Cole as imagens aqui dando Ctrl+V)

---

## Funcionalidades Implementadas

O aplicativo gerado superou as expectativas do MVP e entregou:
1. Autenticacao Simples: Tela de login limpa e segura.
2. Chat Inteligente: Capacidade de registrar gastos em texto livre (ex: "Gastei R$ 35 no almoco hoje"), categorizando a despesa automaticamente e oferecendo dicas amigaveis de economia em tempo real.
3. Painel de Controle (Dashboard): Visao geral imediata de receitas, despesas, saldo do mes e ultimas transacoes.
4. Sistema de Metas: Aba dedicada para criar e acompanhar metas financeiras.
5. Relatorios Visuais: Graficos de facil compreensao, incluindo um grafico de rosca para despesas por categoria e um grafico de barras para o historico de meses.
6. Design Acessivel: Paleta de cores calmante (verde e tons claros), navegacao intuitiva por abas e interface responsiva, alinhados ao conceito de Design Universal solicitado.

---

## Reflexao

### O que funcionou bem?
O processo de refinar o PRD previamente no Copilot foi fundamental. Ter os requisitos muito bem definidos (como o "Design Universal" e as "Funcionalidades-Chave") permitiu que o Lovable acertasse o aplicativo praticamente de primeira. A geracao do banco de dados para persistencia e os graficos visuais foram criados de forma fluida.

### O que nao funcionou como esperado?
Como o processo fluiu muito bem, o maior desafio foi apenas manter o cuidado redobrado com o limite diario de interacoes do Lovable. A ferramenta se mostrou poderosa, mas exige que a engenharia do prompt inicial seja perfeita para nao desperdicar as tentativas gratuitas.

### O que aprendi sobre conversar com IAs?
Aprendi que no Vibe Coding, o segredo nao e programar a maquina, mas sim saber como se comunicar com ela. A engenharia de prompts e a nova logica de programacao. Fornecer contexto, definir o problema, estruturar o publico-alvo e impor regras claras (como o tom educativo) muda completamente a qualidade do resultado gerado pela IA.
