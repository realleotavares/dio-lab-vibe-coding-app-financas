# Finanças Fácil - Vibe Coding

## Sobre o Projeto
Este projeto é a entrega do desafio "Criando um App de Finanças Pessoais com IA" da DIO. O objetivo foi aplicar o conceito de Vibe Coding, utilizando o Microsoft Copilot para refinar um Product Requirement Document (PRD) e o Lovable para gerar um protótipo funcional de um aplicativo de finanças baseado em conversas em linguagem natural.

---

## PRD Refinado no Copilot Web

### Contexto
Desenvolver um aplicativo de organização de finanças pessoais baseado em conversas em linguagem natural. O objetivo é simplificar o controle financeiro, eliminando a necessidade de formulários complexos ou planilhas, e oferecendo uma experiência mais humana e acessível.

### Problema
Usuários frequentemente abandonam aplicativos de finanças porque exigem entradas manuais extensas e oferecem pouca personalização. A proposta é resolver isso com uma interface conversacional e recomendações automáticas de economia.

### Público-alvo
Indivíduos que desejam iniciar o controle de suas finanças de forma prática e descomplicada, especialmente iniciantes sem experiência prévia em gestão financeira.

### Funcionalidades-chave (MVP)
- Registro via chat: Inserir gastos e receitas por meio de conversas em linguagem natural.  
- Classificação automática: Categorizar transações sem esforço manual.  
- Metas financeiras: Criar e acompanhar objetivos como poupar ou quitar dívidas.  
- Dicas de economia: Receber sugestões práticas de um agente financeiro virtual.  
- Relatórios personalizados: Visualizar gráficos e resumos simples adaptados ao perfil do usuário.  

### Design Universal
O aplicativo deve ser projetado com princípios de design universal, garantindo acessibilidade e usabilidade para o maior número possível de pessoas, independentemente de idade, experiência tecnológica ou possíveis limitações físicas/cognitivas. Isso inclui:
- Interface clara e intuitiva.  
- Compatibilidade com leitores de tela.  
- Uso de contrastes adequados e fontes legíveis.  
- Navegação simplificada e consistente.  

### Entregável esperado da IA
- Plano de MVP com telas principais (chat, dashboard, metas, relatórios).  
- Esboço de validação inicial (testes com usuários iniciantes para medir clareza e engajamento).  

### Tom
Educativo, acessível e em português simples, para facilitar a compreensão de usuários iniciantes.

---

## Interações com o Lovable

**Interação 1 (Única e Certeira):**
> Cria um app de finanças pessoais com base no seguinte PRD: [Inclusão do PRD completo detalhado acima].

Nota: O prompt foi tão bem estruturado no Copilot que o Lovable precisou de apenas uma interação principal para gerar o app funcional, fazendo apenas perguntas de clarificação sobre o uso de banco de dados e layout.

---

## Resultado Final no Lovable

**Link de acesso:** https://financafacil-ria.lovable.app

### Telas do App:
*(Adicione as imagens aqui editando pelo GitHub Web e usando Ctrl+V)*

---

## Funcionalidades Implementadas

O aplicativo gerado superou as expectativas do MVP e entregou:
1. Autenticação Simples: Tela de login limpa e segura.
2. Chat Inteligente: Capacidade de registrar gastos em texto livre (ex: "Gastei R$ 35 no almoço hoje"), categorizando a despesa automaticamente e oferecendo dicas amigáveis de economia em tempo real.
3. Painel de Controle (Dashboard): Visão geral imediata de receitas, despesas, saldo do mês e últimas transações.
4. Sistema de Metas: Aba dedicada para criar e acompanhar metas financeiras.
5. Relatórios Visuais: Gráficos de fácil compreensão, incluindo um gráfico de rosca para despesas por categoria e um gráfico de barras para o histórico de meses.
6. Design Acessível: Paleta de cores calmante (verde e tons claros), navegação intuitiva por abas e interface responsiva, alinhados ao conceito de Design Universal solicitado.

---

## Reflexão

### O que funcionou bem?
O processo de refinar o PRD previamente no Copilot foi fundamental. Ter os requisitos muito bem definidos (como o "Design Universal" e as "Funcionalidades-Chave") permitiu que o Lovable acertasse o aplicativo praticamente de primeira. A geração do banco de dados para persistência e os gráficos visuais foram criados de forma fluida.

### O que não funcionou como esperado?
Como o processo fluiu muito bem, o maior desafio foi apenas manter o cuidado redobrado com o limite diário de interações do Lovable. A ferramenta se mostrou poderosa, mas exige que a engenharia do prompt inicial seja perfeita para não desperdiçar as tentativas gratuitas.

### O que aprendi sobre conversar com IAs?
Aprendi que no Vibe Coding, o segredo não é programar a máquina, mas sim saber como se comunicar com ela. A engenharia de prompts é a nova lógica de programação. Fornecer contexto, definir o problema, estruturar o público-alvo e impor regras claras (como o tom educativo) muda completamente a qualidade do resultado gerado pela IA.
