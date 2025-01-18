---
Começado em: 2025-01-17
Terminado em: 
finalizado: 
tags:
  - java
---

# A evolução de Java

- Lançada em **1995** pela *Sun Microsystems*;
- Diferente de outras linguagens Java tem uma forte cultura de inovação e mudança e com isso se atualizava e inovava muito mais rápido que as outras linguagens 

**Atualizações da linguagem**
- Java 1.1 - bibliotecas, redefiniu como eventos são tratados, reconfigurou recursos da biblioteca original 1.0
- Java 2 (segunda geração) - começo da "era moderna", novo pacote foi trazido J2SE (Java 2 Platform Standard Edition) a partir daqui os números de versão foram aplicados nesse produto
- Java J2SE 1.3 - integrou "melhor" o ambiente de desenvolvimento 
-  Java J2SE 1.4exceções encadeadas, I/O (input/output) baseada em canais e a palavra-chave **assert**
- Java J2SE 5 - segunda revolução de Java, tipos genéricos, autoboxing/unboxing, Enumerações, laço **for** melhorado (for-each), argumentos em tamanho variável (*varargs*), importação estática e anotações
- Java J2SE 6 - sem adições de  maiores recursos para a linguagem, aperfeiçoou as bibliotecas de API's, adicionou várias atualizações de pacotes novos e melhorou o tempo de execução, solidificou mais os avanços do J2SE 5
- Java SE 7 e JDK 7 (Microsystems foi adquirida pela Oracle) - Objeto String pode controlar uma instrução swicth, literais in numéricos, try-with-resources, inferência de tipos (via operador losango) n construção de uma instância genérica, tratamento de exceções melhorado onde uma ou mais exceções pode ser capturado pela mesma instrução catch (multicatch)
- Java SE 8 e JDK 8 - expressão lambda, novo operador devido a expressão lambda (->), suporte ao JavaFX substituindo o Swing 

# Origem da linguagem Java

- Criada por **James Gosling**, **Patrick Naughton**, **Chris Warth**, **Ed Frank** e **Mike Sheridan** na *Sun Microsystems* em  **1991**, chamava-se *OAK* e foi renomeada para "**Java**" em **1995**;
- Propósito : ser uma linguagem independente de plataforma e que pudesse ser usada para a criação de múltiplos dispositivos eletrônicos domésticos (torradeira, fornos de micro-ondas  e controle remoto). Com a chegada da Internet logo Java mudou seus planos de eletros doméstico para  a Internet pois também havia o desafio de ser implementada em diversos controladores embutidos 

# Qual a relação entre Java, C e C++?

- Java herda sua sintaxe de C;
- Seu modelo de objetos é adaptado de C++;
- Fácil curva de aprendizagem de java para C/C++ ou vice versa;
- Herda também a filosofia de que "O programador está no comando";
- POO;

# Qual a relação entre Java e C#?

- Java e C# tem a mesma sintaxe de C++;
-  Mesmo modelo de objetos;
- Fácil curva de aprendizagem de Java para C# e vice versa;

# Contribuições da linguagem Java par a Internet

- Simplificou a programação geral da Internet;
- Resolveu o problema de portabilidade e segurança.

## Applets Java

- São programas pequenos projetados para ser transmitido pela internet e executado automaticamente por um navegador Web compatível com Java;
- São usados para exibir dados fornecidos pelo servidor, tratar entradas do usuário ou fornecer funções simples (calculadora de empréstimos);

## Segurança 

- Java garantiu a que Applets fossem baixados dentro de um ambiente que somente podia ter recursos Java.

## Portabilidade

- O mesmo código funciona em todos os computadores.

## O segredo da linguagem Java: o bytecode

- *Bytecode* é um conjunto de instruções altamente otimizado para ser executado pelo sistema de tempo de execução Java, que se chama JVM (Java Virtual Machine);
- JVM foi projetada para ser um interpretador de bytecode, isso facilita a portabilidade do Java, uma vez que qualquer programa Java pode ser executado no sistema se a JVM estiver presente;
- Embora os detalhes da JVM sejam diferentes de uma plataforma para outra, TODAS entendem o mesmo bytecode Java;
- Com a otimização do bytecode não há tanta diferença se o código fosse compilado e não interpretado na questão de agilidade de execução;
- É possível também uma compilação dinâmica de bytecode para código nativo visando melhor desempenho com a tecnologia HotSpot fornece um compilador JIT (just-in-time);
- Quando um compilador JIT faz parte da JVM partes do bytecode é compilada como o Java interpreta muitas coisas em tempo de execução somente algumas partes de código que serão beneficiadas serão compiladas pelo JIT isso já melhora significativamente o desempenho.

 ```ad-tip
 **Pergunte ao Especialista**
 P: Ouvi falar de um tipo especial de programa Java chamado *servlet*. De que se trata?
 R: Um *servlet* é um programa pequeno executado no servidor. Enquanto os applets estendem a duncionalidade de um navegador Web o servlet estende a funcionalidade de um servidor Web. 
```

# O *jargão* Java 

- **Simples**: Java tem um conjuntos de recursos concisos e coeso que a torna fácil de aprender a usar;
- **Segura**: Java fornece um meio seguro de criar aplicativos de Internet;
- **Portável**: Os programas podem ser executados em qualquer ambiente que houver um sistema de tempo de execução Java (JVM);
- **Orientada a objetos**: Incorpora a filosofia de programação orientada a objetos;
- **Robusta**: Incentiva a programação sem  erros por ser fortemente tipada e executar verificações de tempo de execução;
- **Várias threads**: Oferece suporte a programação com várias threads;
- **Neutra quanto à arquitetura**: Java não tem vínculos com uma determinada máquina ou arquitetura de sistema operacional.
- **Interpretada**: Suporte a código para várias plataformas com o uso do bytecode;
- **Alto desempenho**: O bytecode do Java é altamente otimizado para a obtenção de velocidade de execução;
- **Distribuída**: Java foi projetada visando o ambiente distribuído da Internet;
- **Dinâmica**: Os programas Java carregam grandes quantidades de informações de tipo que são usadas na verificação e resolução de acessos a objetos no tempo de execução.

 ```ad-tip
 **Pergunte ao Especialista**
 P: Por que foi necessário criar uma nova linguagem de programação como Java para resolver os problemas de portabilidade e segurança? Uma linguagem como C++ não poderia ser adaptada? Em outras palavras, não poderia ser criado um compilador C++ que gerasse bytecode?
 R: Embora fosse possível de fato criar um compilador C++ gerar algo semelhante a bytecode em vez de código executável, C++ tem reccursos que desencorajem seu uso para a criação de programa da internet, sendo o mais imotante deles o suporte a ponteiros. Um ponteiro é o endereço de algum objeto armazenado na memória. Com o uso de um ponteiro, seria possível acessar recursos dora do programa, o que resultaria em uma falha na segurança. Java não dá suporte a ponteiros, eliminando o problema. 
```

# Programação orientada a objetos

 - Essencial para o java;
 - OOP é uma maneira poderosa de abordar a tarefa de programar;
 - De maneira geral um programa pode ser organizado a partir de duas maneiras: a partir do seu código (o que está ocorrendo) ou a partir dos seus dados (o que está afetado);
 - Programação estruturada é organizada a partir do seu código, código atuando sobre os dados;
 -  POO é a organizada a partir dos dados, dados controlando o acesso ao código, logo um tipo de dado define quais tipo de operações pode ser aplicado a ele;
 - POO tem três importantes pilares: **encapsulamento**, **polimorfismo** e **herança**.

## Encapsulamento

- *Encapsulamento* é um mecanismo de programação que vincula o código e os dados que ele trata, dessa forma mantém os dois seguros de interferência e má utilização externa;
- Os dados podem ser *privados* ou *públicos*;
- Uma classe define a forma de um objeto, ela especifica tanto os dados quanto o código que operará sobre eles.
- Java utiliza da especificação da classe para construir objetos;
- Objetos são instâncias da classe;
- O código e os dados que constituem uma classe são chamados de *membros da classe*;
- Os dados definidos pela classe são chamados de *variáveis*;
- Os códigos que operam sobre esses dados são chamados de métodos membro ou apenas *método*.

## Polimorfismo

- *Polimorfismo* (do grego, "muitas formas") é a qualidade que permite uma interface acesse uma classe geral de ações;
- "Uma interface, vários métodos";
-> Pesquisar mais sobre: método de sobrecarga e de sobrescrita
## Herança

- **Herança** é o processo pelo qual um objeto pode adquirir as propriedade de outro objeto;
- Classificação hierárquica
- Com a herança o objeto só tem que definir explicitamente todas as suas características únicas dentro de sua classe;

# Obtendo o Java Development Kit

- JDK é executado no ambiente de prompt de comando e usa ferramenta de linha de comando. Ele não é um aplicativo de janelas nem um ambiente de desenvolvimento integrado IDE

```ad-tip
**Pergunte ao Especialista**
P: Você diz que a programação orientada a objetos é uma maneira eficaz de gerenciar programas grandes. No entanto, parece que ela pode adicionar uma sobrecarga significativa aos programas relativamente pequenos. Já que você diz que todos o programas Java são, até certo ponto, orientados a objetos, isso é uma desvantagem para os programas pequenos?
R: Não. Em programas pequenos a OO é quase imperceptivel, na medida que os programas crescem é possível integrar mais recursos de OO sem esforço.

```

# Um primeiro programa simples

```run-java
class Example {
	public static void main(String args[]) {
		System.out.println("Olá pessoal da live");
	}
}
```

## Inserindo o programa

- **O nome dado a um arquivo fonte é muito importante**;
- Um arquivo-fonte  é chamado de *unidade de compilação*;
- Java diferencia maiúsculas de minúsculas; 
- O nome do arquivo deve corresponder com o nome da classe (é uma convenção que mantém a organização e manutenção dos programas);

## Compilando o programa 

```run-bash
javac Example.java
```

- O compilador **javac** criará um arquivo chamado **Example.class** contendo a versão em *bytecode* do programa (lembre-se bytecode **não** é código executável)

# Primeiro exemplo de programa linha a linha 

```run-java
/*
	Isso é um comentário de 
	várias 
	linhas
*/
``` 
- Um comentário serve para descrever ou explicar a operação do programa e não é compilado pelo compilador 

```run-java
class Example {
```
- A palavra *class*  é uma palavra reservada do Java usada para definir uma classe e **Example** é o nome da classe 
- A definição da classe começa com **{** e termina com o fechamento **}**
- Os elementos entre as **{ }** são membros da classe

```run-java
// Este é um comentário de apenas uma linha 
```
- Auto explicativo

```run-java
public static void main(String args[]) {
```
- Todos os aplicativos java começam a execução chamando **main()**
- A palavra-chave **public** é um *modificador de acesso* (determina quais partes do programa podem ou não ser acessadas)
- **main()** deve ser declarado como público já que tem que ser chamado por um código de fora de sua classe
- **static** permite que **main()** seja chamado pela JVM antes de qualquer objeto ser criado
- **void** é simplesmente informando ao compilador que o método não retorna nada.
- Em **main()** há somente um parâmetro, **Strings args[]**, que declara um parâmetro chamado args, ele é um array de objetos do tipo String. Nesse caso, args recebe qualquer argumento de linha de comando presente quando o código do programa é executado.
- O **{** sinaliza o início do método e o **}** sinaliza o fim

```run-java
System.out.println("Java drives web.");
```
- Essa linha que esta dentro do método exibe a string "Java drives the Web." seguida de uma nova linha em branco
- **System** é a classe predefinida que dá acesso ao sistema
- **out** é o fluxo de saída que está conectado ao console

# Tratando erros de sintaxe

- Ás vezes erramos ao digitar códigos e o compilador tenta entender o código-fonte não importa o que esteja nele, por tanto o erro que é relatado nem sempre reflete a causa real. Se esquecermos de fechar nosso método **main()**, por exemplo, receberíamos o seguinte erro

![[Pasted image 20250118172337.png]]
- Se tiver um erro de sintaxe você não pode aceitar as mensagens do compilador pois podem estar erradas, análise toda a linha a procura de algo que faça mais sentido.

# Um segundo programa simples

- **Variáveis** é o local nomeado na memória ao qual pode ser atribuído um valor
- Valores podem mudar em tempo de execução

```run-java 

class Example2 {
	public static void main(String args[]) {
		int var1; // Declara uma variável
		int var2;
		
		var1 = 1024; //Atribui um valor a variável 

		System.out.println("var1 contains " + var1);

		var2 = var1 / 2;

		System.out.println("var2 contains va1 / 2");
		System.out.println(var2);
	}
}

```

