# **Glossário**

## **Governança como Versionamento | Release 1.0**

Cada termo está definido em linguagem simples, com uma analogia concreta e a referência ao passo correspondente nos 21 passos. Se você encontrar um desses termos em qualquer artigo da série sem lembrar o que significa, consulte aqui.

Este glossário tem 22 entradas. Vinte e uma integram a tabela de correlação da série (21 conceitos × 21 passos × 21 artigos). Uma, Deploy, fica fora da tabela por razão explicada na própria entrada: pertence à execução, não ao versionamento.

---

### **1\. Acesso (liberdade 0\)**

**Passo 1**

O direito de ver. Qualquer pessoa pode ler tudo que foi decidido, sem precisar pedir permissão a ninguém.

*Como:* O livro de atas na mesa da sala, não trancado no armário.

---

### **2\. Participação (liberdade 1\)**

**Passo 2**

O direito de propor. Qualquer pessoa pode sugerir mudanças, sem precisar ser eleita ou indicada.

*Como:* O microfone aberto na assembleia. Qualquer morador pode pedir a palavra.

---

### **3\. Adaptação (liberdade 2\)**

**Passo 3**

O direito de ajustar. Você pode pegar o que existe e modificar para a sua realidade, sem pedir licença.

*Como:* A receita de família que você herda e tempera do seu jeito.

---

### **4\. Distribuição (liberdade 3\)**

**Passo 4**

O direito de passar adiante. O que você adaptou, outros podem usar. Ninguém tranca o conhecimento.

*Como:* Quem aprendeu a fazer pão e ensina o vizinho. O conhecimento não diminui ao ser passado adiante.

---

### **5\. Catedral**

**Passo 5**

Modo de trabalhar onde um pequeno grupo projeta tudo em segredo e entrega pronto, como um arquiteto que desenha o edifício inteiro antes de mostrar para alguém. Ninguém de fora vê, sugere ou corrige até o produto estar "acabado".

O problema: se o arquiteto errou alguma coisa importante, todo mundo já está constrangido com a obra feita. Erros caros aparecem tarde.

*Como:* Um condomínio onde o síndico contrata a reforma, negocia o preço e assina o contrato — e os moradores só ficam sabendo quando a conta chega.

---

### **6\. Bazar**

**Passo 6**

Modo de trabalhar onde qualquer pessoa pode contribuir, revisar e melhorar a qualquer momento, como uma feira livre onde cada feirante monta sua barraca, qualquer cliente opina e a praça inteira vê o que está acontecendo.

É mais barulhento. Mas erros aparecem mais rápido, porque muitos olhos olham de ângulos diferentes. Não é caos: é uma praça com regras claras de quem pode propor e como as propostas são avaliadas.

Esta série escolhe o bazar.

*Como:* Uma assembleia aberta onde qualquer morador pode propor, qualquer um pode comentar e a decisão final fica registrada para todos verem.

---

### **7\. MAIN (branch principal)**

**Passo 7**

A versão oficial. O documento principal onde está tudo que foi decidido e vale agora. Quando há dúvida sobre o que é oficial, a resposta está aqui.

**Nota sobre nomes:** Em projetos de software, essa versão pode se chamar `main`, `master`, `trunk` ou qualquer outro nome que o grupo escolher. `main` é a convenção mais aceita hoje, depois de um processo gradual de migração que começou por volta de 2020\. O nome não importa: o que importa é que exista uma única versão oficial, com nome claro, que todos reconheçam como a fonte da verdade.

*Como:* O mural oficial do condomínio: o que está ali é o que vale, não o que alguém disse na escada.

---

### **8\. README**

**Passo 8**

O manual da casa. O documento que explica como o grupo funciona: como propor, como revisar, quem decide quando há empate, quais são os limites do que pode ser mudado.

*Como:* O regulamento interno colado na entrada da sede, visível para todos, antes de qualquer reunião começar.

---

### **9\. Issue**

**Passo 9**

Uma proposta escrita. Toda ideia, reclamação ou pedido de mudança vira texto com data e assinatura. Nada muda de boca. A issue fica visível para todos e pode ser respondida, debatida ou arquivada — mas não desaparece.

*Como:* A caixinha de sugestões onde cada bilhete tem nome, data e resposta pública.

---

### **10\. Branch**

**Passo 10**

Uma cópia da versão oficial (MAIN) feita naquele momento exato. A partir daí, você trabalha nessa cópia sem mexer no original — pode rascunhar, testar, errar e refazer quantas vezes precisar. O original continua intacto.

Às vezes a versão oficial avança enquanto você ainda está trabalhando no seu rascunho. Quando isso acontece, você pode atualizar sua cópia com o que mudou no original — é como pedir para alguém te contar o que você perdeu enquanto estava fora, e incorporar isso ao seu trabalho. Se houver partes que conflitam, o grupo decide o que fica.

*Como:* Uma folha em branco para rascunhar enquanto o documento original continua intacto na mesa.

---

### **11\. Commit**

**Passo 10 — segundo gesto**

Uma fotografia assinada do estado atual do seu rascunho naquele momento. Você anota: "dia 15, versão com a regra de votação por maioria simples, incluindo os ajustes que a Maria sugeriu." Essa foto vira um ponto fixo na história.

O commit não é a decisão final — essa vem no merge. É o registro de onde você chegou até aqui, congelado para não perder. Permite voltar para esse ponto depois (revert), comparar com outros momentos, ou juntar partes dele ao documento oficial (merge).

Na prática: a reunião terminou, você anotou no caderno da equipe a versão atual da proposta com essas mudanças, todos viram e assinaram confirmando que essa é a foto do momento. Ninguém pode negar depois que chegaram até ali.

*Como:* Tirar uma foto do rascunho no caderno e assinar embaixo com a data. Não é o livro publicado. É o registro de onde o trabalho estava naquele instante.

**Nota sobre o Passo 10:** Branch e Commit são dois gestos dentro do mesmo passo operacional. Branch é abrir o rascunho. Commit é tirar a foto assinada do ponto em que você chegou. Na tabela de correlação da série (21×21×21), os dois gestos compartilham o mesmo passo e o mesmo artigo de referência. Não há conflito: o passo descreve o fluxo completo do trabalho em rascunho.

---

### **12\. Pull request**

**Passo 11**

O pedido formal de aprovação. Você não empurra sua mudança direto para o documento oficial: pede que o grupo avalie o que você fez no seu rascunho antes de qualquer coisa ser incorporada.

*Como:* Entregar uma emenda ao secretário para ser votada, não alterar a ata sozinho.

---

### **13\. Review**

**Passo 12**

A revisão por pares. Ninguém aprova o próprio trabalho. Sempre outro par de olhos. Não é desconfiança: é arquitetura. O sistema assume que todos erram, e que quem está de fora vê o que quem está dentro não vê mais.

*Como:* O médico que não faz cirurgia em si mesmo. Não por incompetência: por falta de distância.

---

### **14\. Merge**

**Passo 13**

A incorporação. O rascunho aprovado entra na versão oficial. O processo de aprovação terminou. O que estava no caderno paralelo passa a fazer parte do documento que todo mundo usa.

*Como:* A emenda aprovada na assembleia que passa a fazer parte do estatuto. Não substitui o estatuto: integra.

---

### **15\. Transparência / Audit trail**

**Passo 15**

O rastro permanente. Tudo tem data, autor e histórico. Ninguém apaga nada. Qualquer pessoa pode ver quem decidiu o quê, quando e por quê.

*Como:* O extrato bancário que você não pode apagar. Cada lançamento tem data e descrição. Não para punir: para saber.

---

### **16\. Revert**

**Passo 16**

O bisturi. Desfaz uma decisão específica sem mexer nas outras. Você sabe exatamente o que está desfazendo.

*Como:* Cancelar uma lei aprovada em março sem tocar nas outras leis do mesmo ano. O bisturi opera onde você aponta.

Diferença com rollback: revert é cirúrgico. Rollback volta tudo.

---

### **17\. Rollback**

**Passo 17**

A máquina do tempo. Restaura tudo para como estava numa data específica. Usado quando várias decisões em cascata deram errado e desfazê-las uma a uma seria caos.

*Como:* Anular tudo que foi aprovado desde janeiro e voltar para como estava em dezembro.

Diferença com revert: revert desfaz uma coisa. Rollback volta tudo a um ponto anterior.

---

### **18\. Hotfix**

**Passo 18**

A correção de emergência. Vai direto para a versão oficial sem passar pelo fluxo normal, porque a urgência não permite esperar.

**Atenção:** Emergência tem prazo e prestação de contas. Quem acionou o hotfix explica ao grupo depois. A decisão emergencial entra no histórico como qualquer outra. Toda ditadura começa com uma emergência sem prazo. Defina o prazo antes, não durante a crise.

*Como:* Consertar o cano estourado agora. A reforma planejada fica para depois.

---

### **19\. Fork**

**Passo 19**

A ramificação. Alguém pega a versão oficial, faz uma cópia completa e segue um caminho diferente dali em diante. Mesma origem, rumos distintos. Não é traição: é o reconhecimento de que o conflito é irresolvível dentro do sistema atual.

**Limite importante:** Fork funciona para regras, documentos e processos. Para recursos físicos compartilhados — dinheiro, espaço, equipamento — fork não resolve sozinho: você não pode dividir o pátio da escola em dois. Nesses casos, é preciso arbitragem com consequências reais.

*Como:* Uma filial que se emancipa da matriz. Ambas continuam existindo. Nenhuma precisa destruir a outra.

---

### **20\. Tag / Release**

**Passo 20**

O carimbo de estabilidade. Quando o grupo chega num ponto em que as coisas funcionam bem, marca aquela versão com nome e data. Serve como referência futura e como ponto de retorno se as coisas piorarem depois.

*Como:* A edição de um livro: "versão 1.0, aprovada em março de 2025". Não significa perfeição. Significa: até aqui, funciona.

---

### **21\. Merge Conflict**

**Passo 10 — situação específica**

O momento em que dois rascunhos diferentes mexeram no mesmo trecho do documento oficial e o sistema não consegue decidir sozinho qual versão fica. Não é erro: é sinal de que duas pessoas estavam pensando no mesmo problema ao mesmo tempo. Alguém precisa ler os dois lados e decidir.

*Como:* Duas pessoas reescreveram o mesmo parágrafo do regulamento ao mesmo tempo. O sistema avisa: "há conflito aqui". O grupo senta e resolve qual versão entra, ou combina as duas.

**Nota:** Merge Conflict aparece durante o trabalho no Branch (Passo 10\) e se resolve antes do Pull Request (Passo 11). É uma situação, não um passo separado. Integra a tabela 21×21×21 como o conceito de número 21\.

---

### **Deploy (fora da tabela 21×21×21)**

**Passo 14**

A execução. A decisão aprovada vira ação concreta. Precisa ter nome (quem faz), prazo (até quando) e critério de verificação (como o grupo confirma que foi feito). Decisão sem responsável é intenção, não governança.

*Como:* Aprovar a pintura do corredor e nomear quem contrata, com que verba, até quando. Sem esses três, a tinta nunca sai da lata.

**Por que Deploy fica fora da tabela:** Deploy descreve o que acontece quando a decisão sai do sistema de versionamento e encontra o mundo real — quem executa, com que prazo, como se verifica. É um conceito operacional necessário na prática, mas não pertence ao versionamento em si: pertence à execução. Todos os outros 21 conceitos descrevem operações dentro do sistema de registro. Deploy descreve o que vem depois. Por isso integra o protocolo dos 21 passos (que é operacional) mas não integra a tabela de correlação (que mapeia o isomorfismo entre o sistema de versionamento e o sistema de governança). A tabela fecha em 21×21×21. Deploy permanece no glossário e no protocolo como conceito de pleno direito.

---

## **Nota final**

Este glossário tem 22 entradas. Vinte e uma formam a tabela de correlação com os 21 passos e os 21 artigos da série. Uma, Deploy, sustenta o protocolo operacional sem integrar a tabela. Os três sistemas — conceitos, passos, artigos — são isomórficos: não apenas parecidos, mas estruturalmente equivalentes. Essa equivalência está documentada no Apêndice da série.

---

*Governança como Versionamento | Release 1.0*

