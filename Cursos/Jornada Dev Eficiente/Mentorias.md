
# Mentoria Sessão Gratuita - 19/06/2024

Jornada de carreira do Alberto:
- Buscar ser a diferença em tecnicidade (não deseja ser chefe/liderar pessoas);
- Quando quis entrar na Caelum virou commiter do projeto Stela e assim provou seu código sem precisar passar por entrevistas da qual tinha pavor;
- Quando soube que Caelum reconhecia muito instrutores tornou-se um dos melhores instrutores e ascende na carreira;
- Ficou fissurado em treinar pessoas para serem instrutores;
- Quando surgiu a oportunidade de ser sócio Alberto foi escolhido por sua habilidade em executar, conhecimento técnico;
- Hoje tornou-se especialista na Zup;
- Ser um aprendiz serial é essencial;
- Ficou bom em compartilhar conhecimento (post, vídeo etc);
São essas 4 características que forma um Dev Eficiente:
- profundidade técnica (um multiespecialista: ser muito bom/especialista em mais de uma coisa);
- capacidade de execução (ter a "acabativa");
- um aprendiz serial;
- compartilhar conhecimento (impacto horizontal).


- Perguntas da galera:

- Como você gerencia seu tempo de estudo?
Alberto: Eu sou soldado do meu tempo, eu sirvo meu tempo, sei que o tempo é escasso por tanto valorizo o tempo. Eu queria ler livros de história então defini 10 minutos assim que acordo, eu leio DEZ MINUTOS apenas e como não é prioritário eu faço pouco tempo e como não é prioritário faço ser a primeira coisa do dia pq sei que não vou fazer depois. Geralmente estudar é a segunda coisa feita no dia mas sempre respeitando a janela de tempo e sendo constante.

- Você só avança para o proximo tópico se terminar o tópico antes?
Alberto: Não necessariamente, depende da carga cognitiva que o tópico exige se não estiver cansando talvez seja possível fazer mais de um tópico por vez.

- Como você compartilha conhecimento?
Alberto: Tem vezes que a pessoa não está aberta a sugestões de referências/conteudos etc. Sobre compartilhar são passos de formiga toda e qualquer oportunidade de compartilhar: compartilhe!

- Como a gente faz para se tornar a melhor pessoa em um cenário caótico, onde tudo é urgente?
Alberto: Quando eu chego em algum lugar eu sempre invisto tempo em entender o que a empresa precisa.

"Você precisa conquistar o direito de confiar em si mesmo" - Alguma palestra de esporte 

- Como ser reconhecido como sênior?
Alberto: domine a as tecnologias, seja um bom aprendiz, tenha cada vez mais autonomia, por fim pergunte ao seu líder o que falta para alcançar a senioridade



# Mentoria Sessão Gratuita - 26/06/2024

Perguntas da galera:

- Como minimiza bugs?
Alberto: seja questionador e triture o máximo possível dos requisitos, também  gaste energia escrevendo  passo a passo da implementação e fazendo bastante testes.

- 
Alberto: O máximo que pode acontecer é dar errado. Criar a auto confiança é muito importante. Ta tudo bem dar errado. Se exponha a múltiplas situações que vai dar errado

- Como adquirir a capacidade de execução?
Alberto: a famosa "Acabativa". O que ele acha que funciona mesmo é respeitar as janelas de tempo da sua vida. "O seu trabalho se expande de tal maneira a preencher todo seu tempo disponível". Deadlines são muito importantes para que você realize a tarefa

- Como gerar valor na empresa que estou? Como me destacar na empresa?
Alberto: Seja intencional desde o princípio. Entenda exatamente o lugar onde você está. Ganhe consciência sendo observador, feedbacks, reuniões, tenha um olhar analítico. tenha muitas ações intencionais para impulsionar sua carreira

# Mentoria Sessão Gratuita - 10/07/2024
Dinâmica analisar códigos legados
[https://github.com/instructure/canvas-lms/blob/master/app/controllers/quizzes/quiz_submission_questions_controller.rb](https://github.com/instructure/canvas-lms/blob/master/app/controllers/quizzes/quiz_submission_questions_controller.rb "https://github.com/instructure/canvas-lms/blob/master/app/controllers/quizzes/quiz_submission_questions_controller.rb")

[https://github.com/apache/ofbiz-framework/blob/trunk/applications/product/src/main/java/org/apache/ofbiz/shipment/shipment/ShipmentServices.java](https://github.com/apache/ofbiz-framework/blob/trunk/applications/product/src/main/java/org/apache/ofbiz/shipment/shipment/ShipmentServices.java "https://github.com/apache/ofbiz-framework/blob/trunk/applications/product/src/main/java/org/apache/ofbiz/shipment/shipment/ShipmentServices.java")

[https://github.com/facebook/react/blob/main/packages/react-dom-bindings/src/client/ReactDOMComponent.js](https://github.com/facebook/react/blob/main/packages/react-dom-bindings/src/client/ReactDOMComponent.js "https://github.com/facebook/react/blob/main/packages/react-dom-bindings/src/client/ReactDOMComponent.js")

1º rodada - quiz_submission_questions_controller.rb
~não fiz - 

Dicas: Decida um jeito de fazer e invista os 10 minutos nesse jeito, persista mesmo que desconfortável; se vc ficar trocando de técnica várias vezes você irá patinar mais 

É mais ganho "perder" tempo atualizando documento do que não ter algum documento

1º rodada - ShipmentServices.java
No método createShipmentEstimat:
o delegator talvez seja um factory ou builder pra construir a entidade 
dentro do try ele esta buscando o objeto ProductStoreShipmentMeth procurando com base no atributo id dessa entidade e com o queryOne ele ta garantido que só vai trazer
caso não consiga ele vai gerar uma exceção do tipo GenericEntityException e retorna um objeto de erro como resposta 
Esse metodo ta fazendo uma logica para calcular a estimativa do custo de envio (frete)

2º rodada - ShipmentServices.java

DICA:
- Escolhe uma tática e vai lendo o código legado, use o número cabalístico **3** para reler esse tanto de vezes se não deu certo passe para sua próxima tática.
- Seja mais tartaruga do que lebre, ou seja vá com calma nos códigos legados
- A reflexão é o segredo!

# Mentoria Sessão Gratuita - 24/07/2024

*Dinâmica*: Ler coisas desconfortáveis e que iremos abandonar a leitura, o exercício é não abandonar a leitura e nem procurar links externos.

3x 
10 minutos para ler 
5 minutos para escrever (alguém vai apresentar o que leu)

- Tentar escrever um resumo com suas palavras sobre o que entendeu.
- Escrever os pontos que considera que realmente entendeu.
- Escrever os pontos que considera que não entendeu ou que ainda carece de mais entendimento.

1ª Rodada 
Artigo:  [Attention Is All You Need](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- Escrever os pontos que considera que realmente entendeu.
	- Não compreendi o texto
- Escrever os pontos que considera que não entendeu ou que ainda carece de mais entendimento.
	- transdução??
	- o que seria redes neurais sequenciais e  convulocionais ?
	- o que seria Atenção e auto atenção?
	- BLEU é um tipo quantitativo de para medir o que?
	- multi-cabeças? 

2ª Rodada
Artigo:   [Attention Is All You Need](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- Escrever os pontos que considera que realmente entendeu.
		- Resumo: Antigamente era usado os modelos de transdução de sequência que era baseada em redes neurais sequenciais ou convolucionais complexas que incluía o codificador e decodificador. O Google propôs uma nova arquitetura de rede simples chamada Transformers que é baseada unicamente em mecanismo de atenção . Utilizaram experimentos para comprovar a eficácia do modelo que se mostrou mais rápido em relação a modelos antigos, principalmente na tradução do inglês para o francês.
		- Introdução:  As abordagens de ponta para a modelagem de linguagem e tradução automatica costumava ser Redes neurais recorrentes, memória de longo curto prazo (LSTM)  e redes neurais recorrentes com portas em particular. Apesar da eficiência computacional ter sido alcançada atraves da fatoração e computação  condicional a limitação de recorrência 

- Escrever os pontos que considera que não entendeu ou que ainda carece de mais entendimento.
		- mecanismo de atenção ??
	-

3ª Rodada
Artigo:   [Attention Is All You Need](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- Escrever os pontos que considera que realmente entendeu.
	-  Resumo: Antigamente era usado os modelos de transdução de sequência que era baseada em redes neurais sequenciais ou convolucionais complexas que incluía o codificador e decodificador. O Google propôs uma nova arquitetura de rede simples chamada Transformers que é baseada unicamente em mecanismo de atenção . Utilizaram experimentos para comprovar a eficácia do modelo que se mostrou mais rápido em relação a modelos antigos, principalmente na tradução do inglês para o francês.
	- Introdução:  As abordagens de ponta para a modelagem de linguagem e tradução automática costumava ser Redes neurais recorrentes, memória de longo curto prazo (LSTM)  e redes neurais recorrentes com portas em particular. Apesar da eficiência computacional ter sido alcançada através da fatoração e computação  condicional a limitação de recorrência. Mesmo os modelos que utilizavam mecanismos de atenção por ainda depender de ser utilizado em conjunto com redes recorrentes ainda tinham o problema  da distância nas sequências. O Transformer se baseia unicamente em mecanismos de atenção elimina o problema de recorrencia o que facilita a paralelização e dependencias globais;
	- Contexto: 

Dica:
- Tente ler pelo menos 3 vezes;
- Leia por seções e pare para refletir/escrever  o que entendeu;
- Terminou de ler? Releia, leia as notas;

Gerar um post ou video, vir com a apresentação 15 min de apresentação. Tema livre

# Mentoria Sessão Palestras

Feedback do Alberto sobre minha apresentação de Arquitetura Hexagonal
Qual a diferença entre arquitetura hexagonal e limpa?
Por que é uma arquitetura muito boa para microservices?
Sugiro tomar muito cuidado com as analogias. Considero que elas devem ser um exceção na sua condução.. 
Por que é fácil de manter? Como ela te ajuda nisso para além de tentar isolar do mundo externo?
Por que não se acoplar com tecnologias ajuda na testabilidade? 
Quais cenários ela pode ser ineficiente?
Exemplos de código seriam importantes para tirar o exemplo da imaginação da pessoa. 
Sobre falar o que não treinou..

Ele disse que analogias intensifica a carga cognitiva das pessoas pq as tira de um contexto para imaginar outro e então voltar e relacionar o conteúdo. Deixe analogias só para quando o assunto for algo muito tenebroso (quando se tem noção de quantas pessoas sabem dele)


# Mentoria - 07/08/2024

- Design de código é toda decisão de código quando você está codando;
- Design de código é o que mais deteriora o código a longo prazo;
- Independente da sua capacidade técnica, todo sistema vai deteriora com o tempo;
- Design de Arquitetura é mais estável; 
- Você vai deixar decisões ruins no caminho, então você não quer ser melhor para diminuir as decisões ruins?
- O tempo não deve ser ofensor para você não entregar um código com qualidade;
- Trabalhar de fora pra dentro (começar com o endpoint);
- Escrever o fluxo de lógica quando o fluxo é mais complexo;
- Executem o máximo de vezes que puder para minimizar os erros durante o desenvolvimento;

# Mentoria - 14/08/2024 - Sessão de Infraestrutura

**Considerações sobre System Design**
- Software Design - a lógica do software (imagem do lado esquerdo)
- System Design - a parte física/operacional (imagem do lado direito)

![[Pasted image 20240814191904.png]]

- Por que o System Design é importante?
	- É uma habilidade essencial de dominar, principalmente em discussões técnicas
	- Evita vieses (como por exemplo fanboy de tecnologia)
- Processo Arquitetural
	![[Pasted image 20240814192421.png]]
	- Norteia a concepção de um system design
	- Análise Arquitetural - Visa elicitar os requisitos não funcionais
	- Design Arquitetural - começa a desenhar a solução arquitetural 
	- Validação - fase de colocar o desenho em prova (através de uma POC por exemplo)
- Ferramentas úteis durante o processo
	  - Diagramas (Excalidraw, Drawio)
	  - Architecture Decision Records (ADR) 
	  - Calculadores de custo de nuvem
	  - Prova de conceito (POC)
- Requisitos funcionais e  não funcionais

# Mentoria - 21/08/2024


- É indispensável escrever o que você vai codar antes de fato codar 
- Valide o quer você escreveu/entendeu antes de codar poupe tempo e gere código de real valor, nada pior do que fazer código que não foi pedido

# Mentoria - 04/09/2024

- Codamos por 1 hora o seguinte desafio: https://gist.github.com/asouza/a7f27df57e12c82c99a612a0c684515e
# Mentoria - 18/12/2024 - Sessão de Infraestrutura

