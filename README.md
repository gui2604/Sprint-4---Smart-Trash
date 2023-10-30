# Sprint 4 - Smart-Trash
<h1>Smart Trash - Sprint 4 - Edge Computing - IoT ESP32</h1>

<p>Em busca de maneiras eficazes para aprimorar o serviço de coleta de resíduos sem demandar altos investimentos, foi desenvolvida uma abordagem focada na obtenção de informações cruciais. O objetivo era melhorar a gestão desses serviços, resultando em benefícios notáveis, como economia de combustível, redução de despesas com a frota e um impacto ambiental positivo. Assim, surgiu a ideia da Lixeira Inteligente, também conhecida como Smart Trash. Este projeto inovador se concentra na obtenção de dados em tempo real, proporcionando aos centros de gerenciamento de resíduos informações precisas e abrangentes. Essa visão detalhada serve como guia para uma administração mais eficiente e organizada da coleta de resíduos nas áreas urbanas. A Smart Trash é capaz de coletar e transmitir dados instantaneamente a partir de múltiplos pontos de coleta pela cidade. Em comparação com os sistemas antigos, que se baseavam em médias de produção de resíduos ao longo do tempo, essa tecnologia é consideravelmente mais eficiente. Ela permite análises detalhadas, resultando na criação de soluções mais bem planejadas. Essa abordagem inovadora utiliza a tecnologia para aproximar as cidades do ideal de Cidades Inteligentes, promovendo uma gestão de resíduos mais inteligente e sustentável.</p>

<h3>Arquitetura do Projeto</h3>
<div>
  <img src="https://github.com/gui2604/Sprint-4---Smart-Trash/assets/128194162/7b8cf50e-d51d-4f3e-aff9-beb30fdd7e30" width="300px">
  <img src="https://github.com/gui2604/Sprint-4---Smart-Trash/issues/1#issuecomment-1785755950" width="300px">
</div>

<h3>Hardware</h3>
<ul><p>O hardware necessário para a construção e funcionamento da Smart Trash são:</p>
  <li>1x ESP32</li>
  <li>1x Protoboard 830 pontos</li>
  <li>5x LED's(verde, amarelo e vermelho)</li>
  <li>5x Resistores 220V</li>
  <li>1x Sensor ultrassônico - HC-SR04</li>
  <li>1x Sensor de Peso - Célula de carga (simulado pelo potenciômetro)</li>
  <li>1x Cabo microUSB para 3,3V</li>
  <li>6x cabos tipo macho-macho</li>
  <li>12x cabos tipo macho-fêmea</li>
</ul>

<h3>Instruções, dependências e requisitos</h3>
<ul><h4>Requisitos Funcionais</h4>
  <li>A lixeira deverá ser capaz de obter e medir o peso do lixo depositado em seu interior.</li>
  <li>A lixeira deverá ser capaz de traduzir o peso medido para visualização em LED’s (verde, amarelo e vermelho).</li>
  <li>A lixeira deverá ser capaz de detectar o nível, ou seja, a altura do lixo atingido.</li>
  <li>A lixeira deverá ser capaz de detectar em quais locais da borda da lixeira o lixo atingiu sua altura máxima.</li>
  <li>A lixeira devera ter resistencia contra a oxidação e à choques mecânicos.</li>
</ul>
<ul><h4>Requisitos Não-Funcionais</h4>
  <li>A lixeira deverá ser vazada para que não ocorra o acúmulo de líquidos interferindo significativamente na medição do peso do lixo depositado.</li>
  <li>A lixeira deverá possuir uma comunicação eficiente, transmitindo informações para a central em tempo real.</li>
  <li>A lixeira deverá ser capaz de intergir presencialmente com usuários, transmitindo-lhes informações visuais sobre os dados coletados do lixo.</li>
  <li>A lixeira devera ser resistente mecanicamente e quimicamente aos efeitos naturais.</li>
</ul>
<ul><h4>Regras de Negócio</h4>
  <li>A lixeira não poderá ultrapassar 500kg de capacidade de peso, tendo em vista a restrição de acúmulo de lixo depositado, e o comprometimento da estrutura de sustentação da lixeira.</li>
  <li>A lixo depositado não podera ultrapassar 70% do preenchimento de saturação da borda da lixeira, visto o risco de transposição da borda devido à lotação.</li>
</ul>

<h3>Diagrama de Caso de Uso</h3>
<div>
  <img src="https://github.com/gui2604/Sprint-4---Smart-Trash/issues/3#issue-1968933287" width="300px">
</div>


