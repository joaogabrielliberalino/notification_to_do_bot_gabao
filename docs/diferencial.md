\# 🚀 Diferenciais do App de Tarefas (MVP)



O objetivo deste projeto é ir além das listas tradicionais (como Google Tasks e Microsoft To Do), focando na \*\*execução\*\* e na \*\*saúde mental\*\* do usuário. 



Para a nossa primeira versão (MVP), o aplicativo aposta em funcionalidades fáceis de usar e de implementar, mas que resolvem problemas reais de produtividade:



\### 1. Filtro por Nível de Energia 🔋

\* \*\*O problema:\*\* Ferramentas tradicionais ignoram que os humanos ficam cansados. Ter 10 tarefas não adianta se a sua energia está no zero.

\* \*\*A Solução:\*\* Ao criar uma tarefa, o usuário define a energia necessária (Alta, Média ou Baixa). Em dias de exaustão, basta clicar no filtro "Baixa Energia" e o app esconde os projetos pesados, mostrando apenas tarefas simples de executar (ex: "pagar boleto", "limpar a mesa").

\* \*\*Implementação Técnica:\*\* Apenas a adição de um atributo `energia` no objeto da tarefa e um botão de filtro simples no Front-end.



\### 2. Pomodoro Nativo (Timer de Foco) ⏱️

\* \*\*O problema:\*\* Os apps de hoje apenas \*guardam\* a tarefa. Você precisa usar outra ferramenta para focar e executá-la.

\* \*\*A Solução:\*\* Um cronômetro integrado na própria tarefa. O usuário clica na tarefa e aperta "Play". Um timer de 25 minutos inicia na tela, mantendo a pessoa engajada sem precisar sair do aplicativo.

\* \*\*Implementação Técnica:\*\* Lógica básica de cronômetro/temporizador no Front-end associada ao ID da tarefa.



\### 3. A "Regra de Ouro" (Foco Forçado em 3 itens) 🎯

\* \*\*O problema:\*\* Listas com 40 itens causam paralisia e ansiedade.

\* \*\*A Solução:\*\* Uma área principal chamada "Vitória do Dia", onde o sistema \*\*bloqueia\*\* o usuário e permite que ele escolha \*no máximo 3 tarefas\* para focar. Isso força a priorização real e garante o sentimento de dever cumprido ao final do dia.

\* \*\*Implementação Técnica:\*\* Uma validação simples (if array.length >= 3) que desabilita o botão de adicionar na lista principal.



\### 4. Modo Zen (Uma coisa de cada vez) 🧘

\* \*\*O problema:\*\* Muita poluição visual nas listas atuais.

\* \*\*A Solução:\*\* Um botão de "Foco Total". Ao clicar, o aplicativo esconde todas as barras laterais, menus e outras tarefas. A tela fica minimalista e exibe apenas em letras grandes a única tarefa que o usuário precisa fazer naquele exato minuto.

\* \*\*Implementação Técnica:\*\* Manipulação simples de CSS/Estados (ex: React state) ocultando componentes e centralizando o texto.

