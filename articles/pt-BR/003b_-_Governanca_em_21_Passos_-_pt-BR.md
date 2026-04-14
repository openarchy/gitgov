# **Governança em 21 Passos**

## **Versão leiga | Release 1.0**

Cada passo é uma regra simples. Aplicados juntos, por muitas pessoas, geram resultados que nenhum planejador central conseguiria projetar.

**Antes de começar:** o grupo precisa concordar que vai usar este sistema. Sem esse acordo inicial, os passos são imposição, não governança. É o pré-requisito zero.

---

## **OS DIREITOS FUNDAMENTAIS**

### **Passos 1 a 4 | Stallman**

Antes de qualquer processo, o sistema precisa garantir quatro liberdades. Sem elas, o resto é teatro. Inspiradas em Richard Stallman (GNU Manifesto, 1985).

---

**Passo 1 — Todo mundo pode acessar e ler tudo que foi decidido.**

Liberdade de ver (acesso). Nenhuma decisão é secreta. Qualquer pessoa do grupo pode ver o que foi feito, por quem e quando.

*Como:* Um livro de atas aberto na mesa da sala, não trancado no armário do síndico.

---

**Passo 2 — Todo mundo pode propor mudanças.**

Liberdade de participar. Não precisa ser chefe, especialista ou eleito. Qualquer pessoa pode sugerir, questionar ou pedir alteração.

*Como:* O microfone aberto na assembleia do condomínio: qualquer morador pode pedir a palavra.

---

**Passo 3 — Todo mundo pode adaptar o que existe para sua realidade.**

Liberdade de adaptar. Se um modelo funciona em Curitiba, alguém no Pará pode copiar e mudar o que precisar. Sem pedir permissão.

*Como:* Uma receita de família: você herda o pão da avó, mas coloca erva-doce se preferir.

---

**Passo 4 — Todo mundo pode distribuir sua versão para outros.**

Liberdade de compartilhar. O que você adaptou, outros podem usar também. Ninguém tranca o conhecimento.

*Como:* Quem aprende a fazer pão e ensina o vizinho. O conhecimento não diminui ao ser passado adiante.

---

## **O MODO DE TRABALHAR**

### **Passos 5 e 6 | Raymond**

Antes de começar o fluxo, o grupo decide como vai operar. A escolha entre dois modelos muda tudo. Inspirados em Eric Raymond (The Cathedral and the Bazaar, 1999).

---

**Passo 5 — Escolha como o grupo vai trabalhar: em segredo com poucos, ou aberto com todos.**

Catedral ou bazar. Na catedral, um pequeno grupo projeta tudo em segredo e entrega pronto. No bazar, qualquer pessoa pode contribuir, revisar e melhorar a qualquer momento. A catedral produz coisas bonitas, mas se o arquiteto erra, todo mundo paga. O bazar é mais barulhento, mas encontra erros mais rápido. **Esta série escolhe o bazar.**

*Como:* Uma praça com feirantes livres versus uma galeria comercial onde o administrador escolhe quem entra.

---

**Passo 6 — Com muitos olhos, todo problema fica mais fácil de encontrar.**

Revisão aberta. Quando muita gente pode olhar o mesmo documento, os erros aparecem rápido. Não porque as pessoas são geniais, mas porque são muitas e olham de ângulos diferentes.

*Como:* Um texto revisado por vinte pessoas tem menos erros do que o mesmo texto revisado por uma.

---

## **O FLUXO DE VERSIONAMENTO**

### **Passos 7 a 20 | comunidade open source**

O motor do sistema. Como decisões nascem, são avaliadas, aprovadas, executadas, rastreadas, corrigidas ou separadas. Inspirados no Git (criado por Linus Torvalds em 2005\) e nas práticas desenvolvidas pela comunidade open source ao longo das duas décadas seguintes. Torvalds criou o mecanismo. A cultura de governança em torno dele foi construída por muitos.

---

**Passo 7 — Crie a versão oficial do grupo: a fonte única da verdade.**

O MAIN. É o documento principal onde está tudo que foi decidido e vale agora. Pode se chamar `main`, `master`, `trunk` ou qualquer nome que o grupo escolher — o que importa é que exista uma única versão oficial que todos reconheçam. Quando há dúvida, aqui está a resposta.

*Como:* O mural oficial do condomínio: o que está ali é o que vale, não o que alguém disse na escada.

---

**Passo 8 — Escreva as regras num lugar que todos vejam.**

O README. O documento que explica como o grupo funciona: como propor, como revisar, quem decide quando há empate. Antes de jogar, todo mundo conhece as regras.

*Como:* O regulamento interno na entrada da sede, visível para todos.

---

**Passo 9 — Toda sugestão vira proposta escrita.**

Issue: um pedido registrado. Ninguém muda nada de boca. Toda ideia, reclamação ou pedido de mudança se escreve com data e assinatura. Fica visível para todos. Pode ser respondida, debatida ou arquivada — mas não desaparece.

*Como:* A caixinha de sugestões onde cada bilhete tem nome, data e resposta pública.

---

**Passo 10 — Toda proposta ganha um rascunho separado para ser trabalhada.**

Branch: uma cópia da versão oficial feita naquele momento exato. A partir daí, você trabalha nessa cópia sem mexer no original. Pode rascunhar, testar, errar e refazer quantas vezes precisar.

Às vezes a versão oficial avança enquanto você ainda está trabalhando. Quando isso acontece, você pode atualizar seu rascunho com o que mudou no original. Se houver partes que conflitam, o grupo decide o que fica. Esse momento de conflito entre versões tem nome próprio: merge conflict (conflito de versão). Não é erro: é sinal de que duas pessoas estavam pensando no mesmo ponto ao mesmo tempo. Alguém precisa ler os dois lados e decidir.

*Como branch:* Uma folha em branco para rascunhar enquanto o documento original continua intacto na mesa.

*Como merge conflict:* Duas pessoas reescreveram o mesmo parágrafo do regulamento ao mesmo tempo. O sistema avisa. O grupo senta e resolve qual versão entra, ou combina as duas.

**Commit** (segundo gesto dentro do passo 10): Uma fotografia assinada do estado atual do seu rascunho naquele momento. Você anota: "dia 15, versão com a regra de votação por maioria simples, incluindo os ajustes que a Maria sugeriu." Essa foto vira um ponto fixo na história. O commit não é a decisão final — essa vem no merge. É o registro de onde você chegou até aqui, congelado para não perder. Permite voltar para esse ponto depois (revert), comparar com outros momentos, ou juntar partes dele ao documento oficial.

*Como commit:* Tirar uma foto do rascunho no caderno e assinar embaixo com a data. Todos viram e concordaram que essa é a foto do momento. Ninguém pode negar depois que chegaram até ali.

---

**Passo 11 — Quem terminou a proposta pede para incluí-la na versão oficial.**

Pull request: o pedido formal de aprovação. Você não empurra sua mudança direto. Você pede que o grupo avalie.

*Como:* Entregar uma emenda ao secretário para ser votada, não alterar a ata sozinho.

---

**Passo 12 — Toda decisão exige que alguém confira antes de aceitar.**

Review: revisão por pares. Ninguém aprova o próprio trabalho. Sempre outro par de olhos. Não é desconfiança: é arquitetura. O sistema assume que todos erram.

*Como:* O médico que não faz cirurgia em si mesmo. Não por incompetência: por falta de distância.

---

**Passo 13 — Se aprovada, a proposta entra na versão oficial.**

Merge: a incorporação. O rascunho aprovado se junta ao documento principal. O que estava no caderno paralelo passa a fazer parte do documento que todo mundo usa.

*Como:* A emenda aprovada na assembleia que passa a fazer parte do estatuto. Não substitui: integra.

---

**Passo 14 — A decisão aprovada vira ação concreta.**

Deploy: a execução. Não basta decidir: tem que fazer. Defina antes quem executa, até quando e como o grupo verifica que foi feito. Decisão sem responsável é intenção, não governança.

A maioria dos sistemas falha aqui. A decisão existe no papel. A ação não acontece.

*Como:* Aprovar a pintura e nomear quem contrata, com que verba, até quando. Sem esses três, a tinta nunca sai da lata.

**Nota sobre o alinhamento 21×21×21:** Deploy é o único dos 22 conceitos do glossário que vive fora do versionamento em si. Ele descreve o que acontece quando a decisão sai do sistema e encontra o mundo real. Por isso é um passo operacional pleno, mas não integra a tabela de correlação da série (que mapeia o isomorfismo entre versionamento e governança). O conceito que ocupa a posição 21 na tabela é Merge Conflict, descrito no Passo 10\. Mais detalhes no Apêndice.

---

**Passo 15 — Todo erro fica visível para todos.**

Transparência e rastreabilidade. Tudo tem data, autor e histórico. Ninguém apaga rastro. Qualquer pessoa pode ver quem decidiu o quê, quando e por quê. Isso não é punição: é memória institucional.

*Como:* O extrato bancário que você não pode apagar. Cada lançamento tem data e descrição.

---

**Passo 16 — Se uma decisão específica deu errado, ela pode ser desfeita.**

Revert: o bisturi. Desfaz uma mudança pontual sem mexer no resto. Você sabe exatamente o que está desfazendo.

*Como:* Cancelar uma lei aprovada em março sem tocar nas outras leis do mesmo ano.

*Diferença com rollback:* revert é cirúrgico. Rollback volta tudo a um ponto anterior.

---

**Passo 17 — Se várias decisões recentes deram errado, tudo volta a um ponto anterior.**

Rollback: a máquina do tempo. Você escolhe uma data no passado quando as coisas funcionavam bem e restaura tudo para aquele estado. Não é cirúrgico: é um recuo completo.

Use rollback quando houver contaminação em cascata: decisão errada A levou a B e C, que levaram a D e E. Revert uma a uma seria caos.

*Como:* Anular tudo que foi aprovado desde janeiro e voltar para como estava em dezembro.

---

**Passo 18 — Se algo urgente quebra e não pode esperar o fluxo normal, existe a correção de emergência.**

Hotfix: a correção sem fila. Vai direto na versão oficial porque a urgência não permite esperar o processo completo.

**Atenção:** Emergência tem prazo e prestação de contas. Quem acionou o hotfix explica ao grupo depois. A decisão emergencial entra no histórico como qualquer outra. Toda ditadura começa com uma emergência sem prazo. Defina o prazo antes, não durante a crise.

*Como:* Consertar o cano estourado agora. A reforma planejada fica para depois.

---

**Passo 19 — Todo conflito profundo pode gerar uma ramificação da ideia original.**

Fork: seguir outro caminho. Alguém pega a versão oficial, faz uma cópia completa e segue um rumo diferente. Mesma origem, trajetórias distintas. Fork não é traição: é evolução legítima quando o conflito é irresolvível dentro do sistema atual.

**Limite:** Fork funciona para regras, documentos e processos. Para recursos físicos compartilhados — dinheiro, espaço, equipamento — fork não resolve sozinho: você não pode dividir o pátio da escola em dois. Nesses casos, é precisa arbitragem com consequências reais.

*Como:* Uma filial que se emancipa da matriz. Ambas continuam existindo. Nenhuma precisa destruir a outra.

---

**Passo 20 — Toda versão estável merece uma marca.**

Tag ou release: o carimbo de estabilidade. Quando o grupo chega num ponto em que as coisas funcionam bem, marca aquela versão com nome e data. Serve de referência para o futuro e de ponto de retorno se as coisas piorarem depois.

*Como:* A edição de um livro: "versão 1.0, aprovada em março de 2025". Não significa perfeição. Significa que, até aqui, funciona.

---

## **O PRINCÍPIO DE FECHAMENTO**

### **Passo 21**

---

**Passo 21 — Nenhuma versão é final. Inclusive esta.**

O sistema inteiro existe para ser melhorado, questionado e superado. Se parar de mudar, morreu. Se virar dogma, deve ser abandonado.

**Não governam os mais sábios: governam os mais revisáveis.** O valor não está em dominar a linguagem do sistema. Está em aceitar ser corrigido.

**Este sistema existe para ser superado.** Se virar verdade absoluta, falhou. Toda versão deve ser substituída por outra mais simples, mais clara e mais aberta. Esta regra se aplica a si mesma.

---

## **Nota sobre atribuição**

Os passos 1 a 4 são inspirados nas quatro liberdades do software livre, formuladas por Richard Stallman (GNU Manifesto, 1985). Os passos 5 e 6 partem da distinção catedral-bazar de Eric Raymond (The Cathedral and the Bazaar, 1999). Os passos 7 a 20 descrevem práticas que o Git tornou possíveis, desenvolvidas pela comunidade open source ao longo de duas décadas. Torvalds criou o mecanismo. A cultura de governança em torno dele foi construída por muitos. O passo 21 não pertence a ninguém. Ou pertence a todos.

**Sobre o alinhamento 21×21×21:** Este protocolo de 21 passos corresponde, passo a passo, aos 21 conceitos do glossário e aos 21 artigos da série. O alinhamento é isomórfico: os três sistemas têm a mesma estrutura. O único ajuste necessário para fechar o alinhamento foi reconhecer que Deploy (Passo 14\) pertence à execução, não ao versionamento — e que Merge Conflict, descrito dentro do Passo 10, completa os 21 conceitos da tabela como conceito de pleno direito. Mais detalhes no Apêndice da série.

## **Pré-requisitos mínimos**

O grupo precisa conseguir ler e escrever (para o passo 9 funcionar), ter um lugar comum onde registros fiquem acessíveis a todos, e concordar previamente que vai usar este sistema. Um grupo que não pode cumprir esses pré-requisitos precisa resolver isso antes de começar.

---

*Governança como Versionamento | Release 1.0*

