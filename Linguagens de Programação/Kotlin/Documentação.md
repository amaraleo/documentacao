<header>
  <h1>Kotlin</h1>
  <nav>
    <ul>
      <li><a href="#História e Evolução">História e Evolução</a></li>
      <li><a href="#Sintaxe e Semântica">Sintaxe e Semântica</a></li>
      <li><a href="#Palavras Reservadas">Palavras Reservadas</a></li>
      <li><a href="#Interpretador e Compilador">Interpretador e Compilador</a></li>
      <li><a href="#Ambiente de Desenvolvimento">Ambiente de Desenvolvimento</a></li>
      <li><a href="#Comentários">Comentários</a></li>
      <li><a href="#Variáveis">Variáveis</a></li>
      <li><a href="#Sistema de Tipos">Sistema de Tipos</a></li>
      <li><a href="#Caracteres de Escape">Caracteres de Escape</a></li>
      <li><a href="#Operadores">Operadores</a></li>
      <li><a href="#Estruturas de Controle">Estruturas de Controle</a></li>
      <li><a href="#Estruturas de Dados">Estruturas de Dados</a></li>
      <li><a href="#Funções">Funções</a></li>
      <li><a href="#Paradigmas de Programação">Paradigmas de Programação</a></li>
      <li><a href="#Classes">Classes</a></li>
      <li><a href="#Objetos">Objetos</a></li>
      <li><a href="#Programação Orientada a Objetos">Programação Orientada a Objetos</a></li>
      <li><a href="#Atributos">Atributos</a></li>
      <li><a href="#Métodos">Métodos</a></li>
      <li><a href="#Construtores">Construtores</a></li>
      <li><a href="#Encapsulamento">Encapsulamento</a></li>
      <li><a href="#Herança">Herança</a></li>
      <li><a href="#Polimorfismo">Polimorfismo</a></li>
      <li><a href="#Tratamento de Erros e Exceções">Tratamento de Erros e Exceções</a></li>
      <li><a href="#Testes">Testes</a></li>
      <li><a href="#Frameworks">Frameworks</a></li>
      <li><a href="#Bibliotecas">Bibliotecas</a></li>
      <li><a href="#Linguagens de Programação e Seus Usos">Usos</a></li>
      <li><a href="#Plataformas Suportadas">Plataformas Suportadas</a></li>
      <li><a href="#Sites Para Aprofundamento">Sites Para Aprofundamento</a></li>
    </ul>
  </nav>
</header>

<main>
  <section id="História e Evolução">
    <article>
      <h2></h2>
      <p>Kotlin é uma linguagem de programação moderna de código aberto que foi desenvolvida pela JetBrains em 2011. O objetivo principal era fornecer uma alternativa mais concisa, segura e interoperável para o desenvolvimento de aplicativos para a plataforma Java.</p>
      <p>A ideia de criar uma nova linguagem surgiu quando a JetBrains, a empresa responsável pela criação do ambiente de desenvolvimento IntelliJ IDEA, começou a enfrentar dificuldades com o desenvolvimento de seu próprio software. A equipe percebeu que a linguagem Java, embora poderosa e popular, tinha limitações que impediam o desenvolvimento eficiente e seguro de software.</p>
      <p>Kotlin foi projetada para abordar esses problemas, fornecendo uma sintaxe concisa e expressiva, recursos de segurança de tipo, interoperabilidade sem atrito com código Java existente e um ambiente de tempo de execução moderno e eficiente.</p>
      <p>Em 2017, a JetBrains entregou o controle do Kotlin para a comunidade Open Source através da Kotlin Foundation, que é uma organização independente e sem fins lucrativos que visa apoiar o desenvolvimento e a adoção do Kotlin em todo o mundo.</p>
      <p>Desde então, a linguagem tem ganhado cada vez mais popularidade e adoção, sendo utilizada por empresas como Google, Netflix, Uber e Atlassian em seus projetos de desenvolvimento de software. Em 2019, a Google anunciou o suporte oficial ao Kotlin para o desenvolvimento de aplicativos Android, o que impulsionou ainda mais o crescimento e a adoção da linguagem.</p>
    </article>
  </section>
  <section id="Sintaxe e Semântica">
    <article>
      <h2>Sintaxe e Semântica</h2>
      <p></p>
      <ul>
        <li>Ausência de ponto e vírgula: Kotlin não requer o uso de ponto e vírgula para separar instruções individuais</li>
        <li>Inferência de tipo: Kotlin é capaz de inferir automaticamente o tipo de uma variável com base no valor atribuído a ela</li>
        <li>Expressões lambda: Kotlin suporta expressões lambda</li>
        <li>Nullable types: em Kotlin, todas as variáveis são por padrão não nulas.</li>
        <li>Orientação a objetos: Kotlin é uma linguagem de programação orientada a objetos</li>
        <li>Interoperabilidade: Kotlin foi projetado para ser interoperável com outras linguagens de programação, como Java.</li>
      </ul>
    </article>
  </section>
  <section id="Palavras Reservadas">
    <article>
      <h2>Palavras Reservadas</h2>
      <ul>
        <li>abstract</li>
        <li>actual</li>
        <li>annotation</li>
        <li>as</li>
        <li>break</li>
        <li>by</li>
        <li>catch</li>
        <li>class</li>
        <li>companion</li>
        <li>const</li>
        <li>constructor</li>
        <li>continue</li>
        <li>crossinline</li>
        <li>data</li>
        <li>delegate</li>
        <li>do</li>
        <li>dynamic</li>
        <li>else</li>
        <li>enum</li>
        <li>expect</li>
        <li>external</li>
        <li>field</li>
        <li>file</li>
        <li>final</li>
        <li>finally</li>
        <li>for</li>
        <li>fun</li>
        <li>get</li>
        <li>if</li>
        <li>import</li>
        <li>in</li>
        <li>infix</li>
        <li>init</li>
        <li>inline</li>
        <li>inner</li>
        <li>interface</li>
        <li>internal</li>
        <li>is</li>
        <li>it</li>
        <li>lateinit</li>
        <li>link</li>
        <li>local</li>
        <li>loop</li>
        <li>modifers</li>
        <li>module</li>
        <li>native</li>
        <li>new</li>
        <li>noinline</li>
        <li>non-local</li>
        <li>null</li>
        <li>object</li>
        <li>operator</li>
        <li>option</li>
        <li>override</li>
        <li>package</li>
        <li>param</li>
        <li>private</li>
        <li>property</li>
        <li>protected</li>
        <li>public</li>
        <li>receiver</li>
        <li>reified</li>
        <li>repeat</li>
        <li>return</li>
        <li>sealed</li>
        <li>set</li>
        <li>setparam</li>
        <li>suspend</li>
        <li>tailrec</li>
        <li>this</li>
        <li>throw</li>
        <li>try</li>
        <li>typealias</li>
        <li>typeof</li>
        <li>val</li>
        <li>var</li>
        <li>when</li>
        <li>where</li>
        <li>while</li>
        <li>yield</li>
      </ul>
    </article>
  </section>
  <section id="Comentários">
    <article>
      <h2>Comentários</h2>
      <p>Em Kotlin, há dois tipos de comentários:</p>
      <ul>
        <li>Em linha, utilizando: //</li>
        <li>Multi-linha, utilizando /* */</li>
      </ul>
    </article>
  </section>
  <section id="Variáveis">
    <article>
      <h2>Variáveis</h2>
      <p>Variáveis são elementos fundamentais em programação e se referem a um espaço de memória reservado para armazenar um valor. Elas podem ser consideradas como "caixas" que contêm dados e podem ser acessadas e modificadas durante a execução de um programa.</p>
      <p>As variáveis são identificadas por um nome que deve seguir algumas regras, como começar com uma letra ou underscore, não conter caracteres especiais, dentre outras. O valor armazenado em uma variável pode ser de diferentes tipos, como números, texto, booleanos, objetos, etc.</p>
      <br>
      <p>Em Kotlin, há duas palavras reservadas utilizadas para declarar uma variável: var & val. A diferença entre elas é simples:</p>
      <ul>
        <li>var: define uma variável mutável</li>
        <li>val: define uma variável imutável</li>
      </ul>
    </article>
  </section>
  <section id="Sistema de Tipos">
    <article>
      <h2>Sistema de Tipos</h2>
      <p>O sistema de tipos é uma característica importante das linguagens de programação que define as regras para a manipulação e conversão de valores em tempo de execução. O sistema de tipos define os tipos de dados que uma linguagem de programação suporta, como números, strings, booleanos, etc., bem como as operações permitidas entre esses tipos.</p>
      <p>Existem dois tipos de sistemas de tipos: estático e dinâmico. Em um sistema de tipos estático, os tipos de dados são verificados em tempo de compilação, antes do código ser executado. Já em um sistema de tipos dinâmico, a verificação é feita em tempo de execução, conforme o código é executado.</p>
      <br>
      <p>Em Kotlin, o sistema de tipos é estático, onde a verificação de tipos ocorre somente em tempo de compilação, antes da execução do código.</p>
      <article>
        <h3>Tipagem</h3>
        <p>Em Kotlin, a tipagem é forte, não possibilitando a conversão de um tipo em outro. Caso uma variável receba um valor de tipo diferente, esse valor deve ser convertido antes por uma função de conversão, caso contrário será lançado um erro.</p>
      </article>
      <article>
        <h3>Tipos de Dados</h3>
        <ul>
          <li>Char: representa um único caractere, como uma letra ou um símbolo. <br> Exemplos: 'a', '!', '#'.</li>
          <li>String: representa uma sequência de caracteres. <br> Exemplos: "Olá, mundo!", "Python é uma linguagem de programação".</li>
          <li>Inteiros
            <ul>
              <li>Byte: representa um inteiro de 8 bits, com um valor mínimo de -128 e um valor máximo de 127.</li>
              <li>Short: representa um inteiro de 16 bits, com um valor mínimo de -32.768 e um valor máximo de 32.767.</li>
              <li>Int: representa um inteiro de 32 bits, com um valor mínimo de -2.147.483.648 e um valor máximo de 2.147.483.647.</li>
              <li>Long: representa um inteiro de 64 bits, com um valor mínimo de -9.223.372.036.854.775.808 e um valor máximo de 9.223.372.036.854.775.807.</li>
            </ul>
          </li>
          <li>Ponto Flutuante
            <ul>
              <li>Float: representa um número de ponto flutuante de 32 bits, com valores na faixa de +/- 3.40282347 x 10^38 e precisão de cerca de 7 dígitos decimais.</li>
              <li>Double: representa um número de ponto flutuante de 64 bits, com valores na faixa de +/- 1.79769313486231570 x 10^308 e precisão de cerca de 15 dígitos decimais.</li>
            </ul>
          </li>
          <li>Boolean: representa um valor lógico, verdadeiro ou falso. <br> Exemplos: True (verdadeiro), False (falso).</li>
          <li>Array: representa uma coleção ordenada de valores, que podem ser de diferentes tipos. <br> Exemplos: [1, 2, 3], ["maçã", "banana", "laranja"].</li>
        </ul>
      </article>
    </article>
  </section>
  <section id="Caracteres de Escape">
    <article>
      <h2>Caracteres de Escape</h2>
      <p></p>
    </article>
  </section>
  <section id="Operadores">
    <article>
      <h2>Operadores</h2>
      <p></p>
    </article>
  </section>
  <section id="Estruturas de Controle">
    <article>
      <h2>Estruturas de Controle</h2>
      <p></p>
    </article>
  </section>
  <section id="Estruturas de Dados">
    <article>
      <h2>Estruturas de Dados</h2>
      <p></p>
    </article>
  </section>
  <section id="Funções">
    <article>
      <h2>Funções</h2>
      <p></p>
    </article>
  </section>
</main>