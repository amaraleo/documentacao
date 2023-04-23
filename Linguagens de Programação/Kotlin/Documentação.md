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
          <li>Boolean: representam um valor lógico, verdadeiro ou falso. <br> Exemplos: True (verdadeiro), False (falso).</li>
          <li>Array: representam uma coleção ordenada de valores, que podem ser de diferentes tipos. <br> Exemplos: [1, 2, 3], ["maçã", "banana", "laranja"].</li>
        </ul>
      </article>
    </article>
  </section>
</main>