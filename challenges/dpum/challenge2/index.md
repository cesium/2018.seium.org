---
layout: default
---
<section id="challenges">
  <div class="container">
    <section id="desafio2">
      <div class="section-title-container text-center">
        <h2 class="section-title">DPUM - Desafio 2</h2>
      </div>
      <div class="col-md-offset-2 col-md-8 def-text">
        És o cozinheiro chefe de serviço no melhor restaurante de panquecas do mundo. As panquecas são cozinhadas numa fila única sobre uma superficie quente.<br>
        Como parte dos esforços infinitos para maximizar a eficiência, recentemente a Casa decidiu dar-te uma espátula enorme que vira exatamente K panquecas consecutivas, ou seja, nesse intervalo de K panquecas, ele muda o lado com a cara sorridente para um lado sem nada e vice versa. Não muda a ordem da esquerda para a direita das panquecas.<br><br>
        Não é possível virar menos de K panquecas de cada vez com a espátula , mesmo que seja no fim da linha (existem duas fronteiras na superfície de cozedura. Por exemplo, podes virar as primeiras K panquecas, mas não as primeiras K-1 panquecas.<br><br>
        O teu aprendiz, que ainda está a aprender a trabalhar, usou a espátula antiquada, que só vira uma panqueca de cada vez, para virar algumas panquecas e depois correu até a casa de banho com ela, mesmo antes de os clientes chegarem para visitar a cozinha. Tu só tens a espátula enorme, e precisas de a usar para rapidamente virares todas as panquecas para o lado com a cara sorridente, para que os clientes saiam felizes com a sua visita.<br><br>
        Dado o estado atual das panquecas, calcula o número mínimo de usos da espátula enorme que são necessários para deixar todas as panquecas do lado da cara sorridente ou dizer que não é possível.
      </div>
      <div class="col-md-offset-2 col-md-8 def-text">
        <b><span>INPUT:</span></b>
        <p>A primeira linha do input dá o número de casos de teste, T.</p>
        <p>Seguem os T casos de teste. Cada um consiste de uma linha com uma string S e um integer K. S representa a fila de panquecas: cada um dos seus caracteres ou é um + (que representa a panqueca que está inicialmente do lado com a cara sorridente) ou - (que representa a panqueca que está inicialmente do lado sem nada).</p>
        <b><span>OUTPUT:</span></b>
        <p>Para cada caso teste, devolver uma linha que contem Case#x: y, onde x é o número do caso teste (começando em 1) e y ou é IMPOSSIBLE se não existir nenhuma maneira de ter todas as panquecas com o lado feliz para cima, ou um integer que representa o número mínimo de vezes que é necessário usar a espátula enorme para o fazer.</p>
      </div>
      <div class="col-md-offset-2 col-md-8 def-text">
        <b><h3 class="text-center">EXEMPLO:</h3></b><br>
        <b><span>INPUT:</span></b><br>
        <b><h5 style="letter-spacing: 5px; font-family: monospace;">3</h5></b>
        <b><h5 style="letter-spacing: 5px; font-family: monospace;">---+-++- 3</h5></b>
        <b><h5 style="letter-spacing: 5px; font-family: monospace;">+++++ 4</h5></b>
        <b><h5 style="letter-spacing: 5px; font-family: monospace;">-+-+- 4</h5></b><br>
        <b><span>OUTPUT:</span></b><br>
        <b><p>Case #1: 3</p></b>
        <b><p>Case#2: 0</p></b>
        <b><p>Case#3: IMPOSSIBLE</p></b>
      </div>
      <div class="col-md-offset-2 col-md-8 def-text">
        No Case#1 é possível que todas as panquecas fiquem do lado com a cara sorridente virando apenas as 3 panquecas do lado mais a esquerda, chegando a ++++-++-, depois as 3 panquecas mais a direita, chegando a ++++---+ e finalmente as 3 panquecas que restam com o lado sem nada virado para cima. Existem outras maneiras de o fazer virando 3 vezes ou mais, mas nunca virando menos de 3 vezes.
      </div>
      <div class="col-md-offset-2 col-md-8 def-text">
        No Case #2, todas as panquecas já estão viradas para o lado com a cara sorridente, então não existe necessidade de virar nenhuma.
      </div>
      <div class="col-md-offset-2 col-md-8 def-text">
        No Case #3, não existe nenhuma maneira de fazer com que a segunda e a terceira panquecas (a contar da esquerda) fiquem com o mesmo lado para cima, porque quando as tentamos virar ambas viram. Assim, é impossivel que todas as panquecas fiquem do lado feliz para cima.
      </div>
    </section>
</div>
</section>
