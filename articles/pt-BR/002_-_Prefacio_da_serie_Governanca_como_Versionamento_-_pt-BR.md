## **Prefácio da série Governança como Versionamento**

# **Nota do autor: uma mente em formato de árvore torta**

*Este prefácio é uma nota pessoal sobre como o projeto nasceu. Não é artigo da série: é a conversa antes de começar. Se você prefere ir direto ao conteúdo, a Introdução que segue conta por onde a série começa e o que vai encontrar em cada parte.*

---

Meu modo de pensar sempre foi uma árvore mal podada. Galhos para todo lado. Folhas onde não devia. E a sensação constante de que faltava um nó, uma conexão que eu não estava vendo.

Isso me irritava. Parecia que tudo o que eu aprendia ficava flutuando sem lugar. Psicologia num galho, tecnologia noutro, política pendurada numa raiz que não encostava no chão. Um mapa mental que nunca fechava.

Os conselhos eram sempre os mesmos: mindfulness, meditação, respiração. Tentei. Anos. A explicação padrão? Emocional. "Você pensa demais, Gustavo."

Hoje vejo diferente. Não era excesso de pensamento. Era combustível sobrando sem motor definido. Minha cabeça acelerava porque queria encaixar tudo que aprendia num lugar só. E não existia lugar.

Até que a vida fez seu truque favorito.

Num sábado à noite, eu fazia o que faço de melhor: reclamava com convicção sobre como o mundo inteiro estava disfuncional. Meu monólogo clássico. A Rafaela (bióloga, professora, progressista de centro-esquerda, calma como quem já sabe que vai ganhar a discussão) ouviu. Suspirou. E mandou:

"É, Gustavo... Ninguém achou solução para isso ainda. Se você tiver, vai dar uma grande contribuição\!"

Pausa. E então veio a parte que importa: ela não esperou eu terminar de reclamar. Perguntou o que eu faria diferente. Não em teoria. Concretamente. Com quem. Começando por onde.

Eu expliquei. Ela ouviu. E concordou comigo.

Sim. Acontece. Alinhamento planetário. Uma vez a cada 76 anos. Halley feelings.

Mas o que ficou não foi a concordância. Foi a pergunta. O que você faria diferente? Não é pergunta retórica. É a pergunta que obriga a parar de reclamar e começar a construir. Foi ela que destravou o projeto.

Naquele instante a árvore torta se alinhou. Vi o tronco. Vi as raízes. Vi o desenho inteiro.

E o desenho era simples: os problemas que a gente enxerga no mundo (a polarização, a corrupção, as decisões que ninguém sabe quem tomou, as regras que ninguém sabe quem escreveu) não são o problema. São sintomas. O problema real é de arquitetura. O jeito como decisões são feitas, registradas, corrigidas e compartilhadas está quebrado na base.

A solução já existe. Só não estava onde a maioria das pessoas procura.

---

## **1\. O maior desconhecido da era digital**

Em abril de 2005, um programador finlandês irritado criou uma ferramenta em menos de duas semanas. Hoje, vinte anos depois, essa ferramenta coordena praticamente tudo que você usa no celular, no computador, na internet, e nos bastidores do seu banco, da sua loja, do seu aplicativo de mensagens. O nome dela é Git.

Se você perguntar para cem pessoas na rua o que é Git, noventa e oito vão dizer: "Nunca ouvi falar." E essas mesmas pessoas usam aplicativos, sites e serviços que só existem porque milhões de programadores usam Git todos os dias.

Git é invisível. E é, talvez, a tecnologia mais influente que quase ninguém conhece.

O que ele faz é simples de explicar: Git é um sistema onde muitas pessoas trabalham juntas num mesmo projeto sem precisar de chefe central. Toda mudança fica registrada (quem fez, quando, por quê). Qualquer erro pode ser desfeito. Quem discorda pode seguir um caminho próprio sem destruir o original. E o mérito se prova por contribuição visível, não por cargo.

Git é, no fundo, um histórico de decisões com botão de desfazer.

O sistema operacional Linux (que roda em mais de 90% dos servidores do planeta) é feito assim. A Wikipédia opera com lógica parecida. São milhares de pessoas colaborando sem hierarquia rígida, sem votação obrigatória, sem consenso forçado. E funciona. Funciona há duas décadas, com milhões de linhas de código, em escala que nenhuma empresa conseguiu igualar.

Nos anos 90, quando alguém falava de e-mail, a resposta era: "Prefiro mandar carta. Isso nunca vai pegar." O mesmo aconteceu com mensagens instantâneas, chamadas de vídeo, redes sociais. Toda tecnologia que mudou o mundo passou por uma fase em que parecia coisa de nicho. Git está exatamente nesse ponto. Só que a barreira não é o ceticismo: é a linguagem. Os nomes assustam. Os tutoriais esquecem o básico. Os jargões excluem.

Não falta inteligência nas pessoas. Falta tradução.

---

## **2\. O que esta série propõe**

Esta série de 21 artigos faz essa tradução.

Pega 335 anos de pensamento político, filosófico e sistêmico (de John Locke em 1689 até Ethan Mollick em 2024\) e mostra que as ideias mais potentes sobre como organizar gente, corrigir erros e distribuir poder convergem para um modelo que programadores já usam todo dia sem pensar duas vezes.

A tese cabe numa frase: governar é versionar. Errar é registrar. Corrigir é integrar. Autoridade é revisão por pares.

Não é metáfora bonita. É um sistema com 21 passos concretos que qualquer grupo pode aplicar (uma associação de bairro, uma cooperativa, uma escola, um condomínio) sem precisar de computador, sem precisar de programador, sem precisar de permissão.

Antes dos 21 artigos numerados, há uma Introdução que conta a origem da ferramenta e três peças complementares fora da numeração: o glossário com 22 conceitos fundamentais, os 21 passos do protocolo, e o texto "Você nunca parte do zero", que usa uma situação cotidiana para apresentar o sistema a quem nunca ouviu falar de Git. A série propriamente dita abre com Locke. Mas o pano de fundo filosófico da ferramenta (Richard Stallman e as quatro liberdades do software livre, Eric Raymond e a diferença entre catedral e bazar, Linus Torvalds e a construção do Linux) aparece na Introdução que segue este prefácio.

Os 21 artigos percorrem três movimentos. Primeiro, os fundamentos: Locke e o consentimento, Popper e o direito ao erro, Hayek e o conhecimento que nenhum comitê central consegue reunir, Shannon e a diferença entre informação e ruído, Dawkins e as ideias que sobrevivem não por serem verdadeiras, mas por serem boas em se copiar. Depois, os limites: a jaula burocrática de Weber, os vieses de Kahneman, a ansiedade informacional de Wurman, os oito princípios de Ostrom para gerir recursos que pertencem a todos. Por fim, a coordenação em escala: como multidões podem ser mais inteligentes que especialistas, como produção entre pares funciona sem chefe, como o código que rege um sistema é a verdadeira constituição do grupo, como redes definem quem tem poder e quem é invisível.

Termina com alertas. Porque todo sistema aberto atrai quem quer fechá-lo. Yarvin e o risco autoritário. Land e a tecnocracia. Thiel e a tentação da captura. E com uma porta: Mollick e a pergunta sobre o que acontece quando a inteligência artificial entra no jogo.

---

## **3\. A centelha**

Sempre fui movido por aquela fome silenciosa de entender o mundo por dentro. Nunca segui trilha oficial. Um livro puxava outro, um conceito puxava outro. Ia atrás do cheiro da curiosidade sem pedir licença para as disciplinas se conversarem.

Passei anos construindo sistemas de dados. Aprendi algo que parece técnico mas é universal: a forma como você organiza informação determina o que as pessoas conseguem fazer com ela. Um sistema bem desenhado permite que gente comum faça coisas extraordinárias. Um sistema mal desenhado faz até gente competente fracassar.

Não é questão de quem opera. É questão de como o sistema foi montado.

Comecei a perceber que o mesmo vale para decisões coletivas. Reuniões onde ninguém registra nada. Votações sem histórico. Decisões que somem em três meses porque ninguém anotou os termos. Gente competente produzindo resultados ruins, não por incompetência, mas porque a arquitetura do processo era ruim.

E aí veio a pergunta que não me largou: se funciona para código, por que não funcionaria para decisões humanas?

Kathryn Schulz escreveu que cada pessoa projeta uma constelação diferente no mesmo céu, baseada na própria história. Meu céu era caótico. Mas coerente. Os galhos da árvore torta estavam todos lá por algum motivo. Psicologia explicava por que as pessoas decidem torto. Biologia explicava como a colaboração emerge sem coordenador. Tecnologia oferecia a ferramenta que faltava. Filosofia dava a base.

Só faltava alguém me cutucar num sábado à noite para eu enxergar a figura completa.

"Stay hungry. Stay foolish." Jobs popularizou essa frase no discurso de Stanford, mas ela nasceu no Whole Earth Catalog, aquela publicação meio anarquista dos anos 70 que incentivava a exploração intelectual livre. Ela captura meu estilo: faminto, curioso, imprudente na medida certa.

Eu não era ansioso demais. Era curioso demais para caber na caixinha.

---

## **4\. Como ler esta série**

Cada artigo funciona sozinho. Você pode ler na ordem ou pular para o pensador que mais te interessa. Mas existe um fio que conecta todos: a ideia de que ninguém deveria governar sem ser revisável, nenhuma decisão deveria existir sem registro, e nenhum sistema deveria ser grande demais para ser corrigido.

Se em algum momento você pensar "isso faz sentido para a minha realidade", o texto cumpriu seu papel.

Se você discordar de tudo e quiser fazer sua própria versão: melhor ainda. Isso se chama fork. E é exatamente assim que o sistema foi desenhado para funcionar.

Este sistema existe para ser superado. Se virar verdade absoluta, falhou.

Agora, vamos voltar 335 anos. Inglaterra, 1689\. Um médico que nunca exerceu medicina está prestes a virar o conceito de poder de cabeça para baixo. E sem saber, vai escrever o primeiro revert da história.

Mas antes de mergulhar nos pensadores, a introdução que segue conta por onde essa série começou: três frustrações, três respostas e uma ferramenta que mudou o mundo sem que quase ninguém percebesse.

---

## **5\. Referências**

1. TORVALDS, Linus; DIAMOND, David. **Just for Fun: The Story of an Accidental Revolutionary**. Nova York: HarperBusiness, 2001\.

2. RAYMOND, Eric S. **The Cathedral and the Bazaar: Musings on Linux and Open Source by an Accidental Revolutionary**. Sebastopol: O'Reilly, 1999\.

3. SCHULZ, Kathryn. **Being Wrong: Adventures in the Margin of Error**. Nova York: Ecco Press, 2010\.

4. BRAND, Stewart (Ed.). **Whole Earth Catalog**. Menlo Park: Portola Institute, 1968-1972.

5. JOBS, Steve. You've got to find what you love. Discurso de formatura. Stanford University, Palo Alto, 12 jun. 2005\. Disponível em: https://news.stanford.edu/2005/06/14/jobs-061505/. Acesso em: mar. 2025\.

6. CHACON, Scott; STRAUB, Ben. **Pro Git**. 2\. ed. Nova York: Apress, 2014\. Disponível em: https://git-scm.com/book. Acesso em: fev. 2026\.

